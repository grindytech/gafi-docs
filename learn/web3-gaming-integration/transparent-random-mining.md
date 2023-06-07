# Transparent Random Mining

**The Critical Problems of Mining NFTs on Traditional Blockchain Games**

In the traditional way of blockchain gaming, the random mechanism is the missing part despite the fact that randomness is an important component of the game. Typically, a blockchain game will generate NFTs in the game server and then issue them on the blockchain via the admin wallet. In this way, some critical problems occur.

1. Unreliable: The NFT is generated in-game so players don't know if the NFT is really created the way it should be, and how rare it is.
2. The game is not balanced: this has happened a number of times in the blockchain space where admin wallets have created premium NFTs for themselves for a quick profit or a quick rise to the top.
3. The danger of being exploited: since the NFT is issued by the admin wallet which is stored somewhere on the game server, this workaround sometimes turns into a big regret when it gets hacked and causes changes smart contract of the whole game.

**Gafi Transparent Random Mining Mechanism (TRMM)**

TRMM is a trustless mining mechanism in Gafi, let's find out how it works.\
First, conventional computer randomness is pseudo-random, which is the process of generating a random value from an input that can be time, weather, location, etc., anything that is difficult to predict.\
But blockchains require deterministic results — where the same input always produces the same output, so there is no way that a truly random value can be generated in the blockchain itself.

Built with [Substrate](https://substrate.io/), the best-in-class blockchain framework that Gafi generates seeds from the off-chain in each block and then sends to the blockchain as input to TRMM, In this way Gafi builds a new trust randomness mechanism for the Game.

With the combination of Pre-mint and TRMM, gamers can mint NFT in a transparent and reliable way, let's take an example:

<figure><img src="../../.gitbook/assets/Screen Shot 2023-06-05 at 18.28.28.png" alt=""><figcaption></figcaption></figure>

Let's say a racing game wants to generate a collection of 6,300 cars including 5,000 Ferraris, 800 McLarens, and 500 Lamborghinis. The chance of random minting would be:\
Ferrari: 5,000 / 6,300 \* 100 = 79.37%\
McLaren: 800 / 6,300 \* 100 = 12.70%\
And Lamborghini: 500 / 6,300 \* 100 = 7.94%.

With TRMM, NFT mining in blockchain games becomes more transparent. Now that we can see the chance of mining each item in the collection, we can see the random value in each block.
