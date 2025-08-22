# pawn-uci

A modern, asynchronous, and type-safe Rust library for communicating with chess engines using the Universal Chess Interface (UCI) protocol.

This crate is designed to be a robust replacement for older UCI libraries, providing a high-level and easy-to-use API for your chess applications.

## Features

* **Asynchronous-First:** Built with `async/await` for non-blocking communication with engine processes.
* **Type-Safe:** Represents all UCI commands and responses with clear, well-defined Rust types.
* **Ergonomic API:** A high-level `Engine` client that simplifies process management and communication.

## Installation

Add `pawn-uci` to your `Cargo.toml` dependencies:

```toml
[dependencies]
pawn-uci = "0.1.0" # Or the latest version
```

## Basic Usage

The library provides a high-level `Engine` client to manage the communication loop.

```rust

use pawn_uci::{Engine, Go};

#[tokio::main]
async fn main() {
    // TODO
}
```

## License

This project is licensed under the GNU General Public License v3.0

## Contribution

Contributions are welcome! Please feel free to open an issue or submit a pull request.
