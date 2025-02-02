# Linera_Readme
The main crates and directories of this repository can be summarized as follows: (listed from low to high levels in the dependency graph)

linera-base Base definitions, including cryptography.

linera-version A library to manage version infos in binaries and services.

linera-views A library mapping complex data structures onto a key-value store. The corresponding procedural macros are implemented in linera-views-derive.

linera-execution Persistent data and the corresponding logics for runtime and execution of Linera applications.

linera-chain Persistent data and the corresponding logics for chains of blocks, certificates, and cross-chain messaging.

linera-storage Defines the storage abstractions for the protocol on top of linera-chain.

linera-core The core Linera protocol, including client and server logic, node synchronization, etc.

linera-rpc Defines the data-type for RPC messages (currently all client ↔ proxy ↔ chain ↔ chain interactions), and track the corresponding data schemas.

linera-client Library for writing Linera clients. Used for the command-line client and the node service in linera-service, as well as the Web client in linera-web.

linera-service Executable for clients (aka CLI wallets), proxy (aka validator frontend) and servers.

linera-sdk The library to develop Linera applications written in Rust for the Wasm virtual machine. The corresponding procedural macros are implemented in linera-sdk-derive.

examples Examples of Linera applications written in Rust.
