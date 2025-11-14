![Public Beta banner](https://github.com/swiyu-admin-ch/swiyu-admin-ch.github.io/blob/main/assets/images/github-banner.jpg)

# DID TDW - DEPRECATED

[![Build and test](https://github.com/swiyu-admin-ch/did-tdw/actions/workflows/build-and-test.yml/badge.svg)](https://github.com/swiyu-admin-ch/did-tdw/actions/workflows/build-and-test.yml)
[![CodeQL Analysis](https://github.com/swiyu-admin-ch/did-tdw/actions/workflows/codeql-analyze.yml/badge.svg)](https://github.com/swiyu-admin-ch/did-tdw/actions/workflows/codeql-analyze.yml)
[![OSV-Scanner](https://github.com/swiyu-admin-ch/did-tdw/actions/workflows/osv-scanner.yml/badge.svg)](https://github.com/swiyu-admin-ch/did-tdw/actions/workflows/osv-scanner.yml)
[![rust-clippy analyze](https://github.com/swiyu-admin-ch/did-tdw/actions/workflows/clippy.yml/badge.svg)](https://github.com/swiyu-admin-ch/did-tdw/actions/workflows/clippy.yml)

An official Swiss Government project made by
the [Federal Office of Information Technology, Systems and Telecommunication FOITT](https://www.bit.admin.ch/)
as part of the electronic identity (e-ID) project.

**⚠️ PARTIAL IMPLEMENTATION ⚠️**

*Beware, this Rust library implements historical [Trust DID Web - did:tdw - v0.3 specification](https://identity.foundation/didwebvh/v0.3)
only partially while focusing solely on [DID resolution](https://identity.foundation/didwebvh/v0.3/#read-resolve).*

Although the library is still required by [DID Resolver](https://github.com/swiyu-admin-ch/didresolver), it will be kept
in the future as legacy and solely for the sake of backward compatibility, as [newer version of the specifications](https://identity.foundation/didwebvh/v1.0) is currently being implemented.

## Using the library

The library can be used either directly in Rust as is.

### Rust

The library can be used directly in Rust by adding the following dependency to your `Cargo.toml`:

````toml
[dependencies]
did_tdw = { git = "https://github.com/swiyu-admin-ch/did-tdw", branch = "main" }
````

## Benchmarks

All the relevant reports are available [here](criterion/README.md).

## License

This project is licensed under the terms of the MIT license. See the [LICENSE](LICENSE.md) file for details.
