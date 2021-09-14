#Substrate Node Template
A fresh FRAME-based Substrate node, ready for hacking rocket

##Getting Started

Follow these steps to get started with the Node Template

##Rust Setup

First, complete the basic Rust setup instructions.

##Run

Use Rust's native cargo command to build and launch the template node:

###cargo run --release -- --dev --tmp

##Build

The cargo run command will perform an initial build. Use the following command to build the node without launching it:

###cargo build --release


##Embedded Docs

Once the project has been built, the following command can be used to explore all parameters and subcommands:

###./target/release/node-template -h

##Start the development chain with detailed logging:

RUST_LOG=debug RUST_BACKTRACE=1 ./target/release/node-template -lruntime=debug --dev
