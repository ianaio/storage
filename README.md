<div align="center">

  <h1><code>ianaio-storage</code></h1>

  <p>
    <a href="https://crates.io/crates/ianaio-storage"><img src="https://img.shields.io/crates/v/ianaio-storage.svg?style=flat-square" alt="Crates.io version" /></a>
    <a href="https://crates.io/crates/ianaio-storage"><img src="https://img.shields.io/crates/d/ianaio-storage.svg?style=flat-square" alt="Download" /></a>
    <a href="https://docs.rs/ianaio-storage"><img src="https://img.shields.io/badge/docs-latest-blue.svg?style=flat-square" alt="docs.rs docs" /></a>
  </p>

  <h3>
    <a href="https://docs.rs/ianaio-storage">API Docs</a>
    <span> | </span>
    <a href="https://github.com/ianaio/storage/blob/main/CONTRIBUTING.md">Contributing</a>
    <span> | </span>
    <a href="https://discord.com/channels/1247475712001314857/1247475712001314860">Chat</a>
  </h3>

  <sub>Built with 🦀🕸 by <a href="https://rustwasm.github.io/">The IanaIO Rust and WebAssembly Working Group</a></sub>
</div>

This crate provides wrappers for the
[Web Storage API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Storage_API)

The data is stored in JSON form. We use [`serde`](https://serde.rs) for
serialization and deserialization.
