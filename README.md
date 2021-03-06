# Solana Balance Web application

![Solana Balance](solana-balance.png 'Solana Balance')

solana-balance-web is a simple web application to fetch account balance from Solana Mainnet/Testnet/Devnet cluster.

The server code is written in [Rust](https://www.rust-lang.org/) using [actix-web](https://actix.rs/) framework. UX client code is written in ReactJs.

Rust server uses [`solana-account-balance`](https://crates.io/crates/solana-account-balance) crate to fetch account balance. Its code is available on [GitHub](https://github.com/RijulGulati/solana-account-balance).

Detailed instruction for building and running both client and server code is present in their respective directories.

- [server/](https://github.com/RijulGulati/solana-balance/tree/main/server)
- [client ux/](https://github.com/RijulGulati/solana-balance/tree/main/ux)

This application was written with intention of exploring solana rust SDK and learning more about rust language.

## Contributions

I am open to contributions. Please raise an issue or create a Pull Request for the same.

# License

[GPL v3](https://github.com/RijulGulati/solana-balance/blob/main/LICENSE)
