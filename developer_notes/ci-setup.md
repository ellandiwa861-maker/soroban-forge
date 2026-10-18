# CI Setup

We use GitHub Actions with the following jobs:

1. **fmt** – `cargo fmt --check`
2. **clippy** – `cargo clippy -- -D warnings`
3. **test** – `cargo test`
4. **build-wasm** – `cargo build --target wasm32-unknown-unknown --release`
