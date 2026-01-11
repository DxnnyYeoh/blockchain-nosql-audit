## Blockchain-Integrated NoSQL DBMS Audit Trail Prototype

This repository contains a prototype implementation used to evaluate
a blockchain-integrated NoSQL Database Management System (MongoDB)
for secure and tamper-proof audit trails.

MongoDB Change Streams are used to capture real-time database events.
Each audit event is hashed and anchored to an immutable blockchain-style
ledger to ensure non-repudiation and integrity.

This prototype supports the experimental results and discussion
presented in the accompanying academic report.

HOW TO RUN 
npm install
node mongodb/mongoChangeStream.js
node execution/runDemo.js
