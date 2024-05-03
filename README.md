# Redswap Token List
Token list for [redswap.io](https://redswap.io) and [info.redswap.io](https://info.redswap.io/).

# Adding new tokens
## The Approval process
1. Technical team will validate the input to ensure the data is matching with the expected pattern
2. Redswap team will analyze the token and project in terms of value brought into Redstone ecosystem

## Requirements and Recommendations
- One token is accepted per one pull request
- Token data must match contract data
- Token must have a logo
- PR file structure should match the existing structure of the repository (e.g. putting logos in  ```TOKEN_SYMBOL/logo.png```)
- Contract should be verified*
- Project should have a significant role in network's ecosystem
  

_*We highly recommend that the contract is verified as this will be taken into consideration during the evaluation and approval process_

## Steps
- Fork this repository
- Create token folder with similar structure: ```TOKEN_SYMBOL/logo.png```. [Example](https://github.com/AW-House/token-list/tree/main/assets/WETH)
- Edit [tokenlist.json](https://github.com/AW-House/token-list/blob/main/token-list.json) with token data. Example: 
```sh
      {
         "chainId":690,
         "address":"0x4200000000000000000000000000000000000006",
         "symbol":"WETH",
         "name":"Wrapped Ether",
         "decimals":18,
         "logoURI":"https://raw.githubusercontent.com/AW-House/token-list/main/assets/WETH/logo.png",
      },
```
- Create a pull request
