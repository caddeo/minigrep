# Minigrep

As part of the **[The Rust Programming Language](https://doc.rust-lang.org/stable/book/index.html#the-rust-programming-language)** one of the exercises is to write a small grep tool

## Setup and usage

Create a `.txt` file in the root directory, with the text you want to search in

Run the command `cargo run -- {search_term} {txt_file.txt}` 

e.g. 

`cargo run -- to mytextfile.txt` will search for all instances of (case sensitive) `rust` in the file `mytextfile.txt` 

If you want case insensitive searches, you add `IGNORE_CASE` as an environment variable

On bash terminals, you can do the following:

`IGNORE_CASE=1 cargo run -- rUsT mytextfile.txt`

## Run tests

Run `cargo test` to run all the tests.
