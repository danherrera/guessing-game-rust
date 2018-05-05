# Learning Rust: Guessing Game

## What I Learned

### Documentation

Rust's [documentation](https://doc.rust-lang.org/book/first-edition/README.html) is pretty amazing. Very easy to read.

### Build System

Rust uses Cargo to build and manage dependencies. To start a new project, simply run:

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

### Can I add a counter for number of turns based on first tutorial?

Yes. Yes, I can. :)

### How do unit tests work in Rust?

TODO
