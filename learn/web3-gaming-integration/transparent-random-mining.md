# Transparent Random Mining

**The Critical Problems of Mining NFTs on Traditional Blockchain Games**

In the traditional way of blockchain gaming such as the Ethereum smart contract, the random mechanism is the missing part despite the fact random is an important ingredient of gaming.\
Usually, blockchain gaming would generate NFTs in the game server and then issues them on the blockchain through admin wallets.  In this way, some critical problems occur.

1. Unreliable: the NFT is generated in the game so players don't know if the NFT is really created in the way it should be, and the possibility is as rare as it appears to be.
2. The game is not balanced: this has happened a number of times in the blockchain space where admin wallets have created premium NFTs for themselves for a quick profit or a quick rise to the top.
3. Risk of being exploited: since the NFT is issued by the admin wallet which is stored somewhere on the game server, this workaround sometimes turns into a big regret when it gets hacked and the whole game smart contract changes.

**Gafi Transparent Random Mining Mechanism (TRMM)**

TRMM is a trustless mining mechanism in Gafi, let's find out how it works.\
First, conventional computer randomness is pseudo-random, which is the process of generating a value from an input that can be time, weather, location, etc., anything that is difficult to predict.\
But blockchains require deterministic results — where the same input always produces the same output, so there is no way that a truly random value can be generated from the blockchain itself.

Built with [Substrate](https://substrate.io/), the best-in-class blockchain framework that Gafi generates seeds from the off-chain in each block and then sends to the blockchain as input to TRMM, In this way Gafi builds a new trustless randomness mechanism for the Game.

With the combination of Pre-mint and TRMM, gamers can mint NFT in a transparent and reliable way, let's take an example:

<figure><img src="../../.gitbook/assets/Screen Shot 2023-06-05 at 18.28.28.png" alt=""><figcaption></figcaption></figure>

Let's say a racing game generates a collection of 5,000 Ferraris, 800 McLarens, and 500 Lamborghinis. The chance of random minting would be: Ferrari 79.37%, McLaren 12.70%,  and Lamborghini: 7.94%.
