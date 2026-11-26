# oss-tachyon

A prototype Oblivious Syncing Service (OSS) for [Tachyon](https://github.com/tachyon-zcash/tachyon),
imported with its full history from [S1nus/oss-tachyon](https://github.com/S1nus/oss-tachyon).

- `docs/oss-design.md` is the working spec: architecture, wire protocol and audit.
- `oss/crates/oss-core` is the proving and protocol library; `oss/crates/oss` is the JSON-RPC server.

The prototype targets the Tachyon Alpha Testnet and pins mock-proof revisions of
`zcash_tachyon` and `ragu` (see `oss/Cargo.toml`).

## License

Licensed under either of [Apache License, Version 2.0](LICENSE) or
[MIT license](LICENSE-MIT) at your option, as declared by the upstream crates.
