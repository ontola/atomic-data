![Atomic Data](src/assets/atomic_data_logo_stroke.svg)

# `atomic-data-docs`

_Atomic Data is a specification for sharing, modifying and modeling graph data._

View it on [docs.atomicdata.dev](https://docs.atomicdata.dev).
If you're looking for an (early) implementation of Atomic data, check out [atomic](https://github.com/joepio/atomic) (server + cli + lib) and [atomic-data-browser](https://github.com/joepio/atomic-data-browser) (react / typescript).

## About this repo

This repository holds the markdown book for the Atomic Data standard.

You can run it locally using [mdBook](https://github.com/rust-lang/mdBook)

```sh
# This requires at least Rust 1.39 and Cargo to be installed. Once you have installed Rust, type the following in the terminal:
cargo install mdbook
# Install mdbook-linkcheck to prevent broken links in your markdown.
cargo install mdbook-linkcheck
# Serve at localhost:3000, updates when files change.
mdbook serve
```

Publishing is done with Github actions - simply push the master branch.

## Contributing

Add an issue or open a PR!
All thoughts are welcome.
Also, check out the [Discord](https://discord.gg/a72Rv2P).
