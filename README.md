Solana Wallet Airdrop
This is a simple Node.js script to interact with the Solana blockchain network using the @solana/web3.js library. It generates a new keypair, retrieves the public key, checks the wallet balance, prompts for an address to send airdrop SOL, requests an airdrop to the specified address, and finally checks the wallet balance again to confirm the airdrop.

# Prerequisites
. Node.js installed on your machine
. NPM (Node Package Manager)
# Installation
. Clone or download the repository.
. Navigate to the project directory in your terminal.
. Run npm install to install the required dependencies.
# Usage
. Run the script using node <script_name>.js.
. Follow the prompts to enter the public address to send the airdrop.
. The script will display the wallet balance before and after the airdrop.
$ Configuration
. The script is configured to use the Solana devnet cluster by default. You can change this by modifying the clusterApiUrl parameter in the script.
. The default airdrop amount is set to 2 SOL. You can adjust this value in the airDropSol function.
$ Script Explanation
. Generates a new keypair.
. Retrieves the public key from the keypair.
. Establishes a connection to the Solana network.
. Displays the current wallet balance.
. Prompts for a public address to send the airdrop.
. Requests an airdrop of SOL to the specified address.
. Confirms the transaction.
. Displays the updated wallet balance after the airdrop.
