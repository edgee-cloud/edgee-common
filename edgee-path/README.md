<div align="center">

<p align="center">
  <a href="https://www.edgee.cloud">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://cdn.edgee.cloud/img/favicon-dark.svg">
      <img src="https://cdn.edgee.cloud/img/favicon.svg" height="100" alt="Edgee">
    </picture>
    <h1 align="center">Edgee</h1>
  </a>
</p>



# Edgee Path Library

The `edgee-path` library provides utilities for encrypting and decrypting strings, generating random strings, and validating paths based on hostnames. It is designed to be used in scenarios where secure and predictable path generation and validation are required.

## Features

- **Encrypt and Decrypt Strings**: Functions to encrypt and decrypt strings, ensuring data security.
- **Generate Random Strings**: Utility to generate random strings of a specified length.
- **Path Generation**: Generate paths based on hostnames.
- **Path Validation**: Validate paths against hostnames to ensure correctness.

## Installation

To use this library, add `edgee-path` as a dependency in your `Cargo.toml`:

```toml
[dependencies]
edgee-path = "0.1.0"
