# Transparent Random Mining: Gafi's Trustless Mechanism

Traditional blockchain games often lack a reliable random mechanism, despite its critical role in gaming. These games usually generate Non-Fungible Tokens (NFTs) on the game server, which are then issued on the blockchain via an admin wallet. This process leads to several issues:

1. Unreliability: Players cannot verify if the NFTs were created as intended or determine their rarity.
2. Imbalanced Gameplay: Instances have occurred where admin wallets have created premium NFTs for personal gain or swift advancement, disrupting game balance.
3. Exploitation Risk: Since NFTs are issued by an admin wallet stored on the game server, there's a risk of hacking that can lead to changes in the game's smart contract.

To address these issues, Gafi has introduced the Transparent Random Mining Mechanism (TRMM).

I. Gafi’s Transparent Random Mining Mechanism (TRMM)

TRMM is a trustless mining mechanism that provides a solution to the inherent limitations of blockchain randomization. Traditional computers generate pseudo-randomness — random values derived from unpredictable inputs like time, weather, or location. However, blockchains require deterministic results, where the same input always produces the same output, making true random value generation impossible within the blockchain itself.

Gafi, built on the state-of-the-art Substrate blockchain framework, generates seeds off-chain for each block and sends them to the blockchain as inputs for the TRMM. This innovative approach establishes a new, trustworthy random mechanism for gaming.

II. The Combination of Pre-mint and TRMM

By combining Pre-mint and TRMM, gamers can mint NFTs in a transparent and reliable manner. For instance:

<figure><img src="../../.gitbook/assets/Screen Shot 2023-06-05 at 18.28.28.png" alt=""><figcaption></figcaption></figure>

Consider a racing game that wants to generate a collection of 6,300 cars, including 5,000 Ferraris, 800 McLarens, and 500 Lamborghinis. The chances of randomly minting these cars would be:

* Ferrari: 5,000 / 6,300 \* 100 = 79.37%
* McLaren: 800 / 6,300 \* 100 = 12.70%
* Lamborghini: 500 / 6,300 \* 100 = 7.94%

With TRMM, the process of NFT mining in blockchain games becomes transparent. Players can view the chances of mining each item in a collection and observe the random value in each block, ensuring a fair and balanced gaming experience.
