# Wholesale NFT Trades

Wholesale NFT trades involve the bulk buying and selling of Non-Fungible Tokens (NFTs) within a wholesale context. Unlike retail trades, which focus on individual units, wholesale trades are centered around the transaction of larger quantities of NFTs can be from different collections. The wholesale trading system encompasses four distinct trade types, offering traders and collectors convenient options for engaging in wholesale NFT transactions:

1. Set Bundle\
   Set the price for a bundle with a `price`. To set this trade, you must be reserved (lock) the same bundle. This trade may be started in a specific block and period of the block.
2. Buy Bundle\
   Buy a bundle from `Set Bundle` with a `bid price`, the `bid price` must be higher or equal to the `price`.
3. Wishlist\
   Set a trade with a price to buy a bundle. To create this trade, a user must be reserved an amount of \`price\`. This trade can be set to start in a specific block and period of block.
4. Fill Wishlist\
   Sell a bundle `Set Bundle` with `ask price`, `ask price` must be lower or equal to the `price`.

A small deposit must be reserved for any of the trades made, trades can be canceled at any time and all types of reserved (locked) will be unreserved (unlocked).
