# Rust template

This template provides:
- A github action file.
- A cargo config that:
    - Enables "target-cpu=native" by default.
    - Enables incremental compilation in debug mode (only for the crate, not its libraries).
    - Uses only one codegen unit for the release mode.
    - Uses "lto = "thin"" for release mode.
- A coverage script to do run test coverage.
- An AGPL license. If you don't like it, feel free to choose another template. 