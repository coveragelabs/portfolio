# Security Reviews? We cover it

# Contacts

# Portfolio

# Security Review Process
## Setup
### Scope and Complexity
Define the scope of the audit and quantify the complexity of the protocol.
### Quote and Deadline
Give a quote to the client and define deadlines.
### Communication Channel
Create a secure communication channel with the client to ensure that no sensitive information is leaked.

## Context and Cleanup
### Codebase Cleanup
Cleanup the codebase from unused imports, warnings, etc.. [Example](https://www.rareskills.io/post/solidity-style-guide)
### Gas Optimizations
Optimize the protocol for both deployment costs and user gas costs.
### Diagrams and User Flows
We will produce multiple diagrams and user flows of the protocol.
### Static Analysis
We will run multiple static analysis tools in the codebase to cleanup simple issues. 
### First Preliminary Report
A preliminary report is given to the client with the changes made to the codebase during this phase.

## Tests
### Fuzz Testing
We will fuzz the entire protocol.
### Invariant Testing
We will define and run different invariant tests.

## Manual Review
Manual review of the protocol where we do an hands-on deep dive in the protocol to look for complex logic issues.

## Quality Assurance
### Key Management and Roles
What are the different roles of the protocol, what can they do in the protocol, how are keys secured.
### Architecture Review
Review of the architecture of the protocol and suggestions to further improve security and composability.
### Code Maturity
Evaluate code maturity based on Trail of Bit's code maturity table.

## Fix Review and Report
### Second Preliminary Report
A report is sent to the client with the issues found and their repective recommended mitigations. 
### Fix Review
Findings are discussed with the client to determine is the issue is: Fixed, Acknowledged or Team won't fix.
### Final Report
Produce a final report to give to he client that is signed with our PGP key.
