# Midnight Counter Project

## About the Project
This project is a simple counter application built using Midnight's Compact language. It demonstrates how to manage public state on the ledger while utilizing private witnesses for secure interactions.

## Initial Product Idea
A decentralized private contribution tracker that allows individuals to log transparent financial support or milestones towards a community cause without revealing their personal transaction amounts publicly.

## Public State vs Private Witness
- **Public State:** Data that is stored transparently on the ledger and can be viewed by everyone (e.g., the total count).
- **Private Witness:** Confidential inputs known only to the user that are processed locally to update the state securely without leaking sensitive details.
## Local Run & Setup Instructions

To run and test this Midnight Compact contract locally, follow these steps:

1. **Prerequisites Setup:**
   - Ensure you have **Node.js (v22+)** and **Docker** installed and running on your system.
   - Install the Midnight toolchain and Compact compiler following the official documentation.

2. **Clone the Repository:**
   ```bash
   git clone [https://github.com/vidishapanchal143/midnight-counter-project.git](https://github.com/vidishapanchal143/midnight-counter-project.git)
   cd midnight-counter-project
3.**Install Dependencies:**
     npm install
4.**Compile the Compact Contract:**
Compile the contract to generate the ZK circuits and the managed/ directory:    
npx compact compile counter.compact
5. **Run Tests:**
  Execute the test suite to verify contract functionality:
   npm test
