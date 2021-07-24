<b>About:</b><br>
A simple encryption based blockchain with the abilities to create new blocks and transactions. Miners can add confirm/add new blocks to the blockchain.
Developed in NodeJS.

Highlight of main packages:
nodeman: application server/for running the application
jest: for tests
express : for APIs
crypto-js: for encryption

<b>How to setup:</b><br>
1. Run: npm install : to install dependencies
2. Run: node app/index.js : to fire up the main server file
3. Consume the APIs using routes used in the app/indes.js file

<b>NB:</b><br>
You can change the:
DIFFICULTY, MINE_RATE, INITIAL_BALANCE, MINING_REWARD in the config.js file
P2P_PORT and PEERS in your node's environment variables(check P2P_PORT and PEERS in app/p2p-server.js)


Happy coding!


