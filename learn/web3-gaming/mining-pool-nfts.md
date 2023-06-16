---
description: The mining pool mechanism is a new way for Studios to publish NFTs.
---

# Mining Pool NFTs

In the traditional way of publishing NFTs in blockchain games, games are likely to generate in-game items in the game server, which are then minted through the blockchain as NFTs. In this way, the rarity of the NFT is unknown, the number of NFTs is unknown, and the chances of NFT mining are also unknown. More often than not, gamers will lose a lot of money mining a superior item that will never be minted.

Gafi provides a transparent way to publish NFTs under two Mining Pool mechanisms, inspired by the concept of the Video Game - [Loot Table](https://en.wikipedia.org/wiki/Loot\_\(video\_games\)):

1. Stable Mining Pool\
   A stable mining pool is a pool of NFTs (maybe from different collections) and those NFTs must have an infinite supply. Mining opportunity depends on:

* The `weight` or number of NFTs in the pool, the fewer NFTs in the pool, the rarer the NFT.
* NFT Mining Chances will not change after each mining but change after the Mining Pool has changed the weights (by pool admin).

2. Dynamic Mining Pool\
   A dynamic mining pool is a group of NFTs(maybe from different collections) and those NFTs must have a supply. Mining opportunity depends on:

* The `weight` or number of NFTs in the pool, the fewer NFTs in the pool, the rarer the NFT.
* Each NFT minted will be taken out of the pool causing the chances of mining to change slightly.
* NFT mining chance will change after Mining Pool has changed its weight (by pool admin).\
  \
  \
