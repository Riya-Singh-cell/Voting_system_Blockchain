# Voting System

A Blockchain-based Voting System implemented using Solidity. This project allows users to create an election, add candidates, authorize voters, cast votes, and determine the winner.

Features
- **Add Candidates**: Only the owner can add candidates to the election.
- **Authorize Voters**: Only the owner can authorize addresses to vote.
- **Cast Votes**: Authorized voters can vote only once.
- **End Election**: Only the owner can end the election.
- **Get Winner**: Displays the winner after the election ends.

Smart Contract Code
The smart contract is written in Solidity and deployed using Remix IDE.

Files
- `Voting.sol`: Contains the Solidity smart contract code.

 Usage
1. Clone the repository:
```
git clone https://github.com/yourusername/Voting-System.git
```
2. Open the project folder:
```
cd Voting-System
```
3. Deploy the smart contract via **Remix IDE**.
4. Interact with the contract using **MetaMask**.

Deployment
- Open Remix IDE (https://remix.ethereum.org/).
- Paste the `Voting.sol` code and compile it.
- Deploy the contract to a testnet (e.g., Sepolia) using MetaMask.

License
This project is licensed under the MIT License.


