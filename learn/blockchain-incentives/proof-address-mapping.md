# Proof Address Mapping

* **What is Proof Address Mapping(PAM)?**\
  Proof Address Mapping is the easy, secure way to deal with Address Mapping to map two addresses between the Substrate(H256) address and EVM(H160) address. By providing proof that the signature belongs to you.\

* **Why is Gafi Network using Proof Address Mapping?**\
  Inherit the advanced technologies from [Parity](https://www.parity.io/), every Substrate-based project on Kusama/Polkadot ecosystem can offer full EVM implementation. By default, in the case when you transfer some token to the H160 address e.g the Metamask account, and the only private key you know is the Metamask account, not the mapping one(Substrate account). Therefore your Substrate account can't use Substrate API.\
  \
  This limitation can be overcome by several mechanisms e.g [Unified Accounts](https://docs.moonbeam.network/learn/features/unified-accounts/) of [Moonbeam Network](https://moonbeam.network/), which offers a fully EVM compatible platform. The different approaches Moonbeam Network and Gafi Network trying to achieve is Moonbeam's focus on creating a fully Ethereum compatible environment on Polkadot. Gafi going to support the Ethereum environment, and other blockchains in the future. So PAM is the way that fitted to Gafi to the trade-off user's experience for scalability.\

* **How to use Proof Address Mapping?**\
  [Map EVM account with Substrate account](https://wiki.gafi.network/how-to-guides/how-to-map-evm-account-with-substrate-account)

