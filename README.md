# Voting System Smart Contract

This is a simple voting smart contract built in Solidity using Remix IDE.

## Features:
- Add multiple candidates
- Each address can vote only once
- Track total votes for each candidate

## How to Use:
1. Open [Remix IDE](https://remix.ethereum.org/)
2. Paste the Solidity code into a new file (e.g., `VotingSystem.sol`)
3. Select Solidity compiler version 0.8.30
4. Compile the contract
5. Go to the "Deploy & Run Transactions" tab
6. Choose "JavaScript VM" as Environment (if available)
7. In the Deploy section, enter candidates like this:
8. 8. Click **Deploy**
9. Use different addresses to vote (1 time only each)
10. Use `getCandidate` to check vote counts

## Example Functions:
- `vote(uint index)` – Vote for candidate at that index
- `getCandidate(uint index)` – View name and vote count
- `hasVoted(address)` – Check if an address has already voted

## Author:
Bhaskar Rawat (B-Star)

## License:
MIT
