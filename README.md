# Blockchain Contract for Hackathon

This repository contains a blockchain contract developed for a hackathon. The contract, written in Rust, is designed to manage transactions and contributions in a blockchain network.

## Overview

The contract is designed to facilitate a decentralized system of transactions and contributions. It allows users to contribute to the contract, request transactions, and receive payouts. The contract also maintains a history of all payouts and manages the total supply of tokens.

## Features

- **Account Management**: The contract associates each account with the ID of the caller who deploys the contract.
- **Contribution Tracking**: The contract keeps track of all contributors and their contributions. It also maintains a count of contributors and a maximum limit on the number of contributors.
- **Request Management**: The contract manages requests for transactions. Users can make requests, which are stored in a vector.
- **Payouts**: The contract handles payouts to contributors. It keeps track of completed payouts and maintains a history of all payouts.
- **Token Management**: The contract manages the total supply of tokens. Tokens are used to represent contributions and can be exchanged for payouts.

## Contract Structure

The contract is structured as follows:

- `owner`: The account ID of the caller who deploys the contract.
- `contributed`: A vector of contributors.
- `total_supply`: The total supply of tokens.
- `contributors`: A vector of contributors.
- `contributors_count`: The count of contributors.
- `requests`: A vector of requests.
- `completed_payouts`: The count of completed payouts.
- `payout_history`: A vector of payout history.
- `max_contributors`: The maximum number of contributors.
- `contribution_cycle`: The contribution cycle.
- `min_amount`: The minimum contribution amount.
- `balance`: A vector of balances.
- `contract_fee`: The fee for the contract.
- `contract_earnings`: The earnings from the contract.

## Getting Started

To deploy the contract, follow these steps:

1. Clone the repository: `git clone https://github.com/yourusername/yourrepository.git`
2. Navigate to the repository: `cd yourrepository`
3. Compile the contract: `cargo build --release`
4. Deploy the contract: `cargo run --release`

## Testing

To run the tests, use the following command: `cargo test`

## Contributing

Contributions are welcome! Please read the [contributing guidelines](CONTRIBUTING.md) first.

## License

This project is licensed under the [MIT License](LICENSE.md).

## Contact

If you have any questions, feel free to reach out to us at [your contact information].