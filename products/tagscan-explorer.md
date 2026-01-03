# Tagscan Explorer

## Tagscan Explorer

Tagscan is Fintag’s native transaction explorer, engineered to provide transparent, real-time visibility into identity-based crypto activity on the Solana blockchain.

While traditional explorers are built for machine-readable addresses, Tagscan is built for people. It bridges the gap between complex on-chain data and human-readable identities, making blockchain activity easier to verify, audit, and understand.

#### Core Capabilities

Tagscan empowers users and developers to move beyond the "string of characters" and see the actual intent behind transactions.

* Search by Identity: Look up activity using #Fintag handles, wallet addresses, or transaction hashes.
* Track Transaction History: Monitor incoming and outgoing flows associated with a specific identity.
* Deep On-Chain Inspection: View precise timestamps, token types (SOL/SPL), amounts, and finality status.
* Payment Verification: Instantly confirm if a peer-to-peer payment or group split has been successfully completed.

***

#### Why Tagscan?

Traditional block explorers are address-first, making them intimidating for non-technical users. Tagscan introduces an identity-first layer. This aligns with Fintag’s core mission: replacing cumbersome wallet addresses with human-readable handles without sacrificing the decentralization or transparency of the Solana network.

#### Who is it for?

| **User Type**    | **Use Case**                                                |
| ---------------- | ----------------------------------------------------------- |
| Individual Users | Verifying personal payment history and balances.            |
| Developers       | Debugging API integrations and monitoring bot activity.     |
| Communities      | Tracking shared payouts and transparent group transactions. |
| Auditors         | Validating on-chain execution for compliance or reporting.  |

***

#### How It Works

Tagscan operates as an interface layer. It indexes on-chain Solana data and maps it to Fintag identities via our Resolution System.

1. Data Retrieval: Tagscan pulls raw data directly from the Solana ledger.
2. Identity Mapping: The system resolves public keys into Fintag handles.
3. Visualization: The data is presented in a clean, readable format that highlights the "Who" and the "What" of every transaction.

#### Accessing the Explorer

Tagscan is a public, read-only utility. No account or login is required to inspect the network.

> Explore now: [https://tagscan.fintag.io/](https://tagscan.fintag.io/)

***

#### Important Notes

{% hint style="info" %}
* Read-Only: Tagscan is an explorer, not a wallet. It cannot custody funds or initiate transactions.
* Data Accuracy: Data availability is subject to on-chain finality on the Solana network.
* Evolving Features: We constantly update Tagscan with new filters and support for emerging token types.
{% endhint %}
