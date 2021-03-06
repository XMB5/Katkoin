# KatKoin
KatKoin is a new type of cryptocurrency, similar to proof-of-stake cryptocurrencies. If you are new to cryptocurrencies, look at a simple overview of cryptocurrencies [here](simple).

# Aspects of Cryptocurrencies
Read about the volatility of cryptocurrencies [here](aspects)

# Volatility
Read about the volatility of cryptocurrencies [here](Volatility.html)

# Boom
Read about the boom of cryptocurrencies [here](cryptoboom)

## How is KatKoin different than other cryptocurrencies?
KatKoin uses an algorithm related to [Ethereum's Proof of Stake system](https://github.com/ethereum/wiki/wiki/Proof-of-Stake-FAQ) to determine who can validate (also known as mine) the next block. In traditional proof of stake, the next validator is chosen based on their balance. If an address has a high balance, it has a high chance of validating the next block. However, someone cannot validate a block if their computer isn't on. This causes people to leave their computer on. Doing this contributes to the network. The difference between traditional proof of stake and KatKoin's proof of stake is that an address must purchase a KatKoin lottery ticket first.
  A KatKoin lottery ticket is proof that an address burnt coins. Burning coins is paying coins to an invalid address, permanently destroying the coins. Burning more coins awards a larger lottery ticket. A lottery ticket could win multiple times for two weeks after being purchased. After two weeks the lottery ticket is invalid. When purchasing a lottery ticket, an address generates 32 random bytes of data, called the redeem token. This data is hashed and included in the lottery purchase transcation. When validating a block, the redeem token is included in the block. The hash of the redeem token in the block must equal the hash in the lottery ticket purchase transaction. The purpose of the redeem token is to be used as random data to determine the winner of the next lottery. 
