# Ballot Smart Contract

## Overview
This Ethereum-based `Ballot` smart contract enables a voting system where participants can either vote on various proposals directly or delegate their votes to another voter. It is designed to ensure a transparent and secure voting process, preventing issues such as double voting and delegation loops.

## Features
- **Vote Delegation:** Allows voters to delegate their votes to someone else, ensuring their vote counts even if they cannot participate directly.
- **Weighted Voting:** Each voter can have a weight associated with their vote, enhancing the influence of certain votes as determined by the chairperson.
- **Proposal Addition:** Voters can vote on a set of predefined proposals added at the time of contract deployment.
- **Security Checks:** Includes multiple security checks to prevent unauthorized actions and to ensure the integrity of the voting process.
- **Determining Winners:** The contract includes functions to determine the proposal with the most votes and to retrieve the name of the winning proposal.

## Usage
- **Setting up the Ballot:** Initialized with an array of proposals during deployment.
- **Voting Rights:** The chairperson can grant voting rights to participants.
- **Casting Votes:** Voters can cast their votes on preferred proposals.
- **Delegating Votes:** Voters can delegate their voting rights to another trusted voter.
- **Querying Results:** Functions are available to query the winning proposal and the name associated with it.



This smart contract forms the backbone of a decentralized application (dApp) aimed at conducting secure and verifiable voting processes on the Ethereum network.
