### Port sniffer cli written in Rust

Dev usage:

- cargo run 127.0.0.1

Binary usage:

- cargo build --release
- ./target/release/ip_sniffer 127.0.0.1

Available flags:
-h - help
-j - number of threads (defaults to four)
