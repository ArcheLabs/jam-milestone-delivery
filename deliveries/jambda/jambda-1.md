# JAM Milestone Delivery

## Company/Team details

- Company/Team's name: ArcheLabs
- Company/Team's GitHub: [https://github.com/ArcheLabs](https://github.com/ArcheLabs)
- Programming language and language set: Rust (language set B)
- Link/s to previous delivery/ies: None

## Documentation checklist

We declare that:

- [x] we have completed **the Web3 Foundation KYC/KYB process**.
- [x] we used **a clear and permissive open-source license**.
- [x] we submitted **a clear Git history and public, credibly timestamped commits**.
- [x] we used third party libraries for:
  - **cryptographic primitives**: [ark-vrf](https://github.com/davxy/ark-vrf) [ed25519-consensus](https://github.com/penumbra-zone/ed25519-consensus)
  - **codecs**: [SCALE](https://github.com/paritytech/jam-codec).
- [ ] we provided **Gas, trie/DB, signature-verification, and availability (EC/DB) performance tests** to be run on standard hardware.
- [ ] we viewed the following **JAM implementation code** before | during our implementation.
- [x] we have not had private conversations with other implementers.
- [x] we have not had concerns about collusion.
- [x] we agree to a recorded interview by the _Polkadot Technical Fellowship_ on any matter arising from this milestone submission.
- [x] we understand that this milestone submission will need to be ratified with an on-chain remark by the _Polkadot Technical Fellowship_ before it can be merged.

## Context

As an independent developer, after learning about JAM/PVM, I realized that this is exactly the architecture needed for Web3 to scale toward real-world, large-scale applications. Therefore, I began implementing the JAM protocol in the second half of 2025. Compared with other teams, my development timeline was relatively tight.

Despite that, I still completed Jambda and fulfilled the requirements of the M1 stage. Jambda provides a Rust-based implementation of a JAM client, which currently supports block import, along with the development and verification work required for subsequent stages. In addition, during this process, I wrote around twenty technical documents to record my understanding of the Graypaper, key design decisions, implementation details, and lessons learned.

In the next stage, Jambda will complete the following work on top of the M1 foundation:

- Extensive architectural refinement and optimization
- Implementation of a PVM-to-native recompiler
- Practical development work for the M2 stage
- Expanding the range of practical PVM use cases, including exploration of small-LLM execution on the PVM

## Deliverables

- [x] 1. Validating Node Path
- [ ] 2. Non-PVM Validating Node Path
- [ ] 3. Light Node Path

- **Milestone:**: 1

| Number | Deliverable          | Link                                                                                                                          | Notes |
| ------ | -------------------- | ----------------------------------------------------------------------------------------------------------------------------- | ----- |
| 1.     | Jambda Source Code   | [jambda](https://github.com/ArcheLabs/jambda)|Main Rust implementation of the Jambda JAM client for the M1 scope.|
| 2.     | Binary Releases      | [jambda-release](https://github.com/ArcheLabs/jambda-release)|Precompiled binaries for testing and evaluation.|
| 3.     | Public Commit Hashes | [polkadot.subscan.io](https://polkadot.subscan.io/account/12gj7WyRWVAbmUXk1nLoGaK1Um47tcmxdd138DSuYZgngetP)|commit hash records|
|        |                      | [assethub-polkadot.subscan.io](https://assethub-polkadot.subscan.io/account/12gj7WyRWVAbmUXk1nLoGaK1Um47tcmxdd138DSuYZgngetP) |earlier commit hash records|

## Additional Information

None.
