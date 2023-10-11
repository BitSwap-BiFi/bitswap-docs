# On-Chain Swaps with Bitswap

Bitswap enables a variety of on-chain swaps, providing users with multiple options for securely exchanging assets on the Bitcoin network. This section explores the capabilities of Bitswap, including Partially Signed Bitcoin Transactions (PSBT), scriptless swaps, atomic swaps, and the role of Client Side Validation.

## Partially Signed Bitcoin Transactions (PSBT)

### What are PSBTs?

Partially Signed Bitcoin Transactions (PSBTs) are a standard format for partially signed Bitcoin transactions. They allow multiple parties to collaboratively create a transaction without revealing sensitive details, making them a key component of secure swaps.

### How Bitswap Uses PSBTs

Bitswap leverages PSBTs to facilitate on-chain swaps securely and privately. PSBTs allow users to propose, review, and approve transaction details without revealing critical information, such as private keys. This collaborative approach ensures that the swap can be verified and executed safely.

## Scriptless Swaps

### The Scriptless Approach

Bitswap introduces scriptless swaps, a technique that simplifies the on-chain swap process by eliminating the need for complex scripts. This approach enhances both the privacy and security of asset exchanges.

### Benefits of Scriptless Swaps

- **Improved Privacy:** Scriptless swaps reduce the amount of information publicly recorded on the blockchain, enhancing user privacy.

- **Simplified Transactions:** Eliminating complex scripts makes swaps more straightforward and less prone to errors.

- **Enhanced Security:** Reducing the reliance on intricate scripts minimizes the risk of potential vulnerabilities.

## Atomic Swaps

### The Atomic Swap Mechanism

Bitswap supports atomic swaps, a trustless and decentralized method for exchanging assets between different blockchains. Atomic swaps ensure that both parties receive their assets simultaneously, or the swap does not occur at all.

## Role of Client Side Validation

In all on-chain swap methods, Client Side Validation plays a vital role. It allows users to verify the integrity of the swap, confirm the accuracy of transaction details, and ensure that their assets remain secure throughout the exchange process. Client Side Validation empowers users with full control over their private keys and assets, enhancing the trustlessness of on-chain swaps.

---

This section provides an overview of how Bitswap facilitates on-chain swaps with PSBT, scriptless swaps, and atomic swaps while highlighting the significance of Client Side Validation in these processes. Further sections in your documentation can dive deeper into the practical use of these swap methods, provide code examples, and address specific use cases for each type of swap.
