# Learning Fundamental Rust

---

### Using Cargo

When you start reading about Rust, you will soon meet [Cargo](https://doc.rust-lang.org/cargo/), the standard tool used in the Rust ecosystem to build and run Rust applications. 
Here we want to give a brief overview of what Cargo is and how it fits into the wider ecosystem and how it fits into this training.

### Installation

#### Rustup (Recommended)

You can follow the instructions to install cargo and rust compiler, among other standard ecosystem tools with the [rustup](https://rustup.rs/) tool, which is maintained by the Rust Foundation.
Along with cargo and rustc, Rustup will install itself as a command line utility that you can use to install/switch toolchains, setup cross compilation, etc.

### The Rust Ecosystem

The Rust ecosystem consists of a number of tools, of which the main ones are:

- `rustc`: the Rust compiler which turns .rs files into binaries and other intermediate formats.
- `cargo`: the Rust dependency manager and build tool. Cargo knows how to download dependencies hosted on https://crates.io and it will pass them to rustc when building your project. Cargo also comes with a built-in test runner which is used to execute unit tests.
- `rustup`: the Rust toolchain installer and updater. This tool is used to install and update rustc and cargo when new versions of Rust is released. In addition, rustup can also download documentation for the standard library. You can have multiple versions of Rust installed at once and rustup will let you switch between them as needed.

### Reference

Link: https://google.github.io/comprehensive-rust/