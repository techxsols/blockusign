Project Description
This project combines Multi-sigs with AA & Off-chain compute to allow decentralized organizations to sign PDF documents. This would allow DAOs to produce invoice-documents, tax-forms, and other legal documents in a more decentralized fashion. This is crucial for on-boarding the next-generation of Web3 users since it allows Web3 organizations/entities to trustlessly satisfy obligations in the Web2/legal world.

How it's Made
We used Safe AA SDK to produce a multi-sig Smart Wallet that can send transactions without having to pay for gas. We then use Chainlink Functions to call an API that can take the data signed by the multisig and put it into a fillable PDF. We made our own API that allows Chainlink Functions to be used for POST-requests that are non-idempotent.
