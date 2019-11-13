# Election process using BlockChain

# Structure

.
├── build                   # Compiled files 
├── contracts               # Smart Contracts written in Solidity language
│   ├── Election.sol        # Election Contract 
│   ├── Migration.sol       # Migration Contract
├── migrations              # Migration Files for intitialization and deployment
├── src                     # Website data using HTML, CSS, JS & web3
├── test                    # Automated tests
├── truffle.js              # Configuration file for running in truffle environment
└── README.md             


# Objectives:
Create a front end using HTML/CSS/JS and web3 for users to interact and cast their vote.
Remove the possibility for a user to cast votes more than once.
Remove the need of a centralized server by using blockchain with nodes that share all the data and code in the network.
Ensuring all votes are counted.


# Case Tests:

Case 1: Ensuring that votes can be casted only between 10:00 AM to 7:00 PM.
Case 2: Adding the constraint for the ganache users to enter username and password for verification to vote.

# Schema:
![Schema](https://drive.google.com/file/d/10TJeR7HlytDmZswFo5C9Scnz-T2ZNOFK/view?usp=sharing)



