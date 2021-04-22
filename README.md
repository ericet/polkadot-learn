Datahub Link: https://datahub.figment.io/services/polkadot

* git clone https://github.com/ericet/polkadot-learn.git
* cd polkadot-learn
* npm install
* Replace < API KEY > in .env file with your API KEY

#1
* node connect.js

#2
* node create_account.js
* Copy address and mnemonic from output of connect.js into .env

#3
* node query.js

#4
* Get free testnet tokens: https://faucet.figment.io/
* node transfer.js

#5
* node create_account.js
* Copy address and mnemonic from output into PROXY_MNEMONIC and PROXY_ADDRESS from .env
* node staking_proxy.js

#6
* node tx_search.js