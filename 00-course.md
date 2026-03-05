---
course: Cardano Go PBL
credential: Cardano Go Developer
audience: Go developers new to Cardano, or Cardano developers learning Go
duration: 8-12 hours (full course)
prerequisites: Go programming fundamentals, basic terminal familiarity
status: readiness-assessed
created: 2024-12-12
last_updated: 2026-03-05
notes: 44 SLTs across 10 modules. Readiness: 6 Ready, 33 Needs Context, 5 Needs Human. Critical path is Apollo/gOuroboros/Adder documentation.
---

# Cardano Go PBL

## Course Purpose

Learn Cardano development using Go and the Blink Labs toolchain. Build applications that interact with the Cardano blockchain using gOuroboros for node communication, Apollo for transaction building, Adder for chain indexing, and Bursa for wallet management.

## Learning Outcomes

By the end of this course, learners will be able to:

1. Connect to Cardano nodes using gOuroboros
2. Build and submit transactions using Apollo
3. Index blockchain events using Adder
4. Manage wallets programmatically with Bursa
5. Interact with smart contracts from Go applications
6. Debug cross-stack blockchain applications

---

## Modules

### Module 099: Intro to Go

Background knowledge for Cardano developers learning Go.

- **099.1**: I can find and fix bugs in a Go program using debugging tools.
- **099.2**: I can work with Go's type system to make different parts of a program fit together.
- **099.3**: I can build a command-line tool with multiple commands using the Cobra library.
- **099.4**: I can create a web API that handles requests and sends responses using Fiber in Go.

### Module 100: Prerequisites + Tools of Cardano Go Development

Background knowledge about Cardano development for Go developers.

- **100.1**: I know enough about Cardano to start this course.
- **100.2**: I understand the essentials of how Ouroboros works.
- **100.3**: I understand why Bursa was built and what problems it solves.
- **100.4**: I understand why Apollo was built and what problems it solves.
- **100.5**: I understand why Adder was built and what problems it solves.
- **100.6**: I understand why Cardano Up was built and what problems it solves.
- **100.7**: I know how this course works and I'm ready to get my hands dirty.

### Module 101: Interacting with the Cardano Node

Options for accessing a Cardano Node and basic operations.

- **101.1**: I can run the gOuroboros Starter Kit.
- **101.2**: I can fetch specific blocks from a remote Cardano Node using Node-to-Node communication.
- **101.3**: I can check sync state of the blockchain from a Cardano Node using either Node-to-Node or Node-to-Client communication.
- **101.4**: I can fetch information about the Node's mempool contents.

### Module 102: Building Simple Transactions

Essentials of transaction building with Apollo.

- **102.1**: I can create a wallet with Bursa.
- **102.2**: I can build a simple transaction with Apollo.
- **102.3**: I can sign a transaction manually and programmatically.
- **102.4**: I can submit a transaction to a node with gOuroboros.
- **102.5**: I can set a validity interval for a transaction.
- **102.6**: I can add simple metadata to a transaction.

### Module 201: Reacting to Chain Events

Monitor blockchain activity by watching the chain and filtering events.

- **201.1**: I can run the Adder Starter Kit.
- **201.2**: I can configure Adder to connect to a Cardano Node.
- **201.3**: I can filter by event type.
- **201.4**: I can filter transactions by address.
- **201.5**: I can filter transactions by policy id.
- **201.6**: I can filter blocks by pool id.

### Module 202: Querying the Blockchain

View global or historical blockchain data beyond event handling.

- **202.1**: I understand the role of an indexer and practical concerns for using one.
- **202.2**: I understand the limits of an event handler and when I need a more general query.
- **202.3**: I can store and retrieve data using Adder.
- **202.4**: I can select the right query provider for my application.
- **202.5**: I can enrich event data with query data.

### Module 203: Applications and Smart Contracts

Build transactions that interact with smart contracts.

- **203.1**: I can compare types written in Aiken, blueprint files, and Go code.
- **203.2**: I can build a transaction that mints or burns tokens with a native script.
- **203.3**: I can build a transaction that mints or burns tokens with a validator script.
- **203.4**: I can build a transaction that unlocks tokens from a validator script.
- **203.5**: I can build a transaction that writes datum to a new UTxO.
- **203.6**: I can build a transaction that specifies a redeemer.

### Module 204: Serializing Data

Understand how data is stored on the blockchain.

- **204.1**: I can read datums and redeemers from deserialized CBOR.
- **204.2**: I can compile a parameterized validator script.
- **204.3**: I can read a transaction event that includes a smart contract interaction.
- **204.4**: I can manipulate and understand deserialized CBOR.
- **204.5**: I can read a protobuf spec to understand standardized data.
- **204.6**: I can reference the CDDL to understand what's in transaction CBOR.

### Module 301: Debugging

What to do when none of the above actually works.

- **301.1**: I can find and fix bugs in my application.
- **301.2**: I can use Go Profiler and the debug port to diagnose bugs.
- **301.3**: I know where to go for help.

### Module 302: Contributing

- **302.1**: I can make a PR to a Blink Labs repository.
