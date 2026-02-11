# Contributing to sshez

## Prerequisites

sshez is written in Rust. You'll need to install the [Rust toolchain](https://www.rust-lang.org/tools/install) to build and contribute to sshez.

### Code Quality

To lint Rust code, run:

```bash
cargo clippy --fix --allow-dirty -- -W clippy::pedantic
```

To format Rust code, run:

```bash
cargo fmt
```

### Unit Tests

To run unit tests, run:

```bash
cargo test
```

### Publishing

Publishing is done using [`maturin`](https://www.maturin.rs/).

To install `maturin`, install the Python requirements:

```bash
pip install -r requirements.txt
```
