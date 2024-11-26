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


# Cargo Workspace for Edgee

This repository is a Cargo workspace that contains multiple common utilities for the Edgee project. A Cargo workspace allows us to manage multiple related Rust packages together, sharing dependencies and configuration.

## Structure

The workspace is organized into several packages, each providing specific utilities or functionalities required by the Edgee project. This modular approach helps in maintaining clean and reusable code.

## Utilities

The following utilities are currently available in this workspace:

- **edgee-path**: provides utilities for encrypting and decrypting strings, generating random strings, and validating paths based on hostnames.

More utilities will be added as the project evolves.

## Getting Started

To get started with this workspace, ensure you have Rust and Cargo installed. You can then build and run the packages using Cargo commands.

```sh
# Build all packages in the workspace
cargo build

# Run tests for all packages
cargo test
```