# Election process using BlockChain

# Structure

.<br/>
├── build                   # Compiled files <br/>
├── contracts               # Smart Contracts written in Solidity language<br/>
│   ├── Election.sol        # Election Contract <br/>
│   ├── Migration.sol       # Migration Contract<br/>
├── migrations              # Migration Files for intitialization and deployment<br/>
├── src                     # Website data using HTML, CSS, JS & web3<br/>
├── test                    # Automated tests<br/>
├── truffle.js              # Configuration file for running in truffle environment<br/>
└── README.md             <br/>


# Objectives:
Create a front end using HTML/CSS/JS and web3 for users to interact and cast their vote.
Remove the possibility for a user to cast votes more than once.
Remove the need of a centralized server by using blockchain with nodes that share all the data and code in the network.
Ensuring all votes are counted.


# Case Tests:

Case 1: Ensuring that votes can be casted only between 10:00 AM to 7:00 PM.
Case 2: Adding the constraint for the ganache users to enter username and password for verification to vote.

# Schema:
![Schema](https://github.com/pizzasahu/Voting-Ethereum-blockchain/blob/master/DS_mini_project_schema.png)



