# create-spl-token-tool


Python script to faciliate the creation of token on the Solana blockchain (SPL Tokens). In fact, you just have to run one command to create a token instead of the multiple commands if you use the `spl-token` command-line utility directly from a terminal.

  
## Installation
1. Once you've satisfied the requirements in the prerequisites file:

2. Clone the repo :  
  
    `git clone https://github.com/Temitopeishola/Temitope_sol_token.git`
  
3. Change directory and run :  
  
    ```
    cd create-spl-token-tool
    py create-spl-token.py <NETWORK> <TOKEN_NUMBER> <KEYPAIR> <PUBKEY> <DECIMALS_NUMBER> <MINT_AUTHORITY_OPTION>
    ```
  
  With:  
  * `<NETWORK>` : network on wich you want to create a token (`mainnet-beta` or `devnet`)
  * `<TOKEN_NUMBER>` : number of token you want to mint
  * `<KEYPAIR>` : path of your keypair file
  * `<PUBKEY>` : your public key (Must be the address associated to the keypair file)
  * `<DECIMALS_NUMBER>` : number of decimals of your token (By default, SPL-token has 9 decimals)
  * `<MINT_AUTHORITY_OPTION>` : if you want to disable future token mint set to `disable`, set to `enable` otherwise
