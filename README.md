# monero-cli

Command-line wallet tooling built on the adjacent `monero-rust` library.

This repository was extracted with its source history from the former `monero-rust` Cargo
workspace. It remains path-connected to an adjacent checkout during the repository separation;
the dependency will move to a released `monero-rust` version once the library is publishable.

```sh
cargo test
cargo run -- --help
```
