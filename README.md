# Apstark

**Apstark** is a layer 2 ZK rollup blockchain built on top of the Aptos network.

## Repositories

- [**stark-evm-adapter**](https://github.com/sota-zk-labs/stark-evm-adapter/tree/aptos-adapter): A library providing
  utilities to parse and manipulate the output of STARK proofs. It enables the generation of "split proofs" required for
  proof verification on Ethereum.
- [**navori**](https://github.com/sota-zk-labs/navori): A verifier contract for Apstark.
- [**irelia**](https://github.com/sota-zk-labs/irelia): A Rust-based service for submitting verification proofs.
- [**ionia**](https://github.com/sota-zk-labs/ionia): A contract handling data availability for the rollup.
- [**orn**](https://github.com/sota-zk-labs/orn): A tool managing contract's constants for the verifier.
- [**ornn**](https://github.com/sota-zk-labs/ornn): A tool for synchronizing verifier states.
- [**madara**](https://github.com/sota-zk-labs/madara): A client for Starknet integration.
- [**madara orchestrator**](https://github.com/sota-zk-labs/madara-orchestrator): An additional service running
  alongside Madara for enhanced orchestration.