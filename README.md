# Coinbase Staking API Postman Collection

This repoisotry contains a Postman collection for the Coinbase Staking API,
allowing developers to easily test out the API endpoints prior to code integration.

## Getting Started

Import both the `Coinbase Staking API.postman_collection.json` and `Ed25519_Keys.postman_environment`

Go to [Coinbase Developer Portal](https://portal.cdp.coinbase.com) and create a new
API key. By default, the key should be create in the Ed25519 format and will be
Base64 encoded. The legacy key type (EcDSA) is not supported by this environment.

Paste the Key Name and Key Secret into the corresponding environment variables, ensuring
they are surrounded by double quotes so they import as strings correctly.

All endpoints are configured to use either the Holesky Ethereum network or
Solana Devnet.

## License

The *Coinbase Staking API Postman Collection* is free and open source and
released under the [Apache License, Version 2.0](LICENSE).

The collection is only available for demonstration purposes.
