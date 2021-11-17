# minigrep

## Description

A simplified grep tool.

## Usage in Linux

In a terminal at this repository, run these commands:
- `cargo build --release`, if the project is not built yet
- `./target/release/minigrep <query> <optional_text_file_name>`

To use case insensitive, prefix the second command with `CASE_INSENSITIVE=1 `.
In case the `<optional_text_file_name>` is not provided, `stdin` is used instead.
