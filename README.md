# Learning Rust: Guessing Game

## What I Learned

### Documentation

Rust's [documentation](https://doc.rust-lang.org/book/first-edition/README.html) is pretty amazing. Very easy to read. In fact, [this tutorial](https://doc.rust-lang.org/book/first-edition/guessing-game.html) came from the documentation!

### Build System

Rust uses Cargo to build and manage dependencies. Rust's dependencies are called "crates" and the preferred open source "repository" (formally known as "registry" in the Rust community) is [crates.io](http://crates.io).

To start a new project, execute:

```shell
cargo new project_name --bin
```

Within the `project_name` directory a `Cargo.toml` file will be generated. As an Android developer, I relate this file as the `build.gradle` in an Android project, as it is where one defines dependencies.

To build the project, execute:

```shell
cargo build
```

To run the project, execute:

```shell
cargo run
```

I was impressed by the comprehensive warnings the rust compiler demonstrated (e.g. warning when a `Result` is not used).

### Language Features

Based on this tutorial, I find a lot of similarities with Kotlin (immutability, inferred type, and pattern matching).

## Questions

### How do unit tests work in Rust?

TODO
