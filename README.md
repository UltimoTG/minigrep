# Minigrep - simple grep in Rust

## Prerequisites

- Make sure you have Rust installed on your machine
- `rustc --version`
- `cargo --version`

## To run a case sensitive search
- From the root of this project, run
  - `cargo run [text to search] [file to search in]`
  - Ex. `cargo run to poem.txt`
- Search results will be shown in the terminal

## For case insensitive search:
- Set an environment variable named `CASE_INSENSITIVE` to any value
    - On a Mac, `export CASE_INSENSITIVE=1`
- Unset this variable to go back to case sensitive search
    - On a Mac, `unset CASE_INSENSITIVE`

## To output the search results to a file
  - `cargo run [text to search] [file to search in] > [file name]`
  - Ex. `cargo run to poem.txt > output.txt`
