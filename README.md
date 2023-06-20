# rust-test-repo

> _Rustaceans_

> Rust is a language empowering everyone to build _reliable_ and _efficient_ software

- __Performance__

> Blazingly fast and memory-efficient: with no _runtime_ or _garbage collector_, it can
power performance-critical services, run on _embedded devices_, and easily integrate with
other languages

- __Reliablity__

> Rust's _rich type system_ and _ownership model_ guarantee _memory-safety_ and _thread-safety_ -- enabling you to eliminate many classes of bugs at compile-time

- __Productivity__

> Rust has great documentation, a friendly _compiler_ with useful _error messages_, and top-notch tooling -- an _integrated package manager_ and _build tool_, _smart multi-editor support_ with _auto-completion_ and _type inspections_, an _auto-formatter_, and more

- Rust in production

> _fast, low-resource, cross-platform solutions_

> from _embedded devices_ to _scalable web services_

- __WebAssembly__ :)


## `rustup` installation

- `rustup` -- command line tool for managing Rust versions and associated tools

```bash
curl --proto '=https' --tlsv1.2 https://sh.rustup.rs -sSf | sh
rustup docs
rustup update
rustup self uninstall
```

- `rustc` - Rust compiler

```bash
rustc --version
echo $PATH
rustc <main.rs> && ./<main.rs>
```

### IDE support

- `rust-analyzer`

### Rust formatter tool

- `rustfmt`

indent with 4 spaces not tabs

### Rust Package Manager

- `cargo` -- Rust's build system and package manager

```bash
cargo --version
cargo new <project>
cargo new --vcs=git <project>
cargo build && ./target/debug/<exe>
cargo run
cargo check
cargo build --release
```

- `Cargo.toml` -- `TOML` -- _Tom's Obvious, Minimal Language_ cargo's config format
- `Cargo.lock` -- keeps track of the exact versions of the dependencies 

> `Cargo docs`

```console
cargo doc
cargo doc --open
```
