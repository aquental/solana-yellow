# Solana Yellow

## Solana token: **yellow**

## SmartContract: staking with _variable yield_

```script
solana --version
> solana-cli 1.17.25 (src:d0ed878d; feat:3580551090, client:SolanaLabs)
```

```script
cargo install spl-token-cli
> package `spl-token-cli v3.3.0`
```

```script
solana balance 9TAiq2rgwPhfrksxFUtEtqCEra7qBZ3ZtkSgtzUCnZq9 --url devnet
> 8.000005 SOL
```

[solscan](https://solscan.io/address/9TAiq2rgwPhfrksxFUtEtqCEra7qBZ3ZtkSgtzUCnZq9?cluster=devnet)

## create a new token

```script
spl-token create-token --url devnet

Creating token 6fEuaENy9uqhGirFsgcr5nHCNNDAy4LcsnqFr2zaHvJE under program TokenkegQfeZyiNwAJbNbGKPFXCWuBvf9Ss623VQ5DA

Address:  6fEuaENy9uqhGirFsgcr5nHCNNDAy4LcsnqFr2zaHvJE
Decimals:  9

Signature: 5bZZSqhXNk7V479dLLwDGZcLb23FQ3MBafZhkSsV6akEaByxitdgpxZpNqWZU1S183YuvVN944X5FDLHmhL3Wfvm
```

**Token address**: _6fEuaENy9uqhGirFsgcr5nHCNNDAy4LcsnqFr2zaHvJE_

```script
spl-token create-account 6fEuaENy9uqhGirFsgcr5nHCNNDAy4LcsnqFr2zaHvJE --url devnet

Creating account Exs22npoeZZNQEo2neCfKb57AtT3CSBVotZdySrEeZRD

Signature: 2QsFs6vGwTyRvH1vK4BMn5RfTVAbXdmLFZWmphVLzrvgRCWft1546aTnJhMUJHgQgbH87RSuzJKD1ncS1yQpByZG
```

**Account**: _Exs22npoeZZNQEo2neCfKb57AtT3CSBVotZdySrEeZRD_

```script
spl-token mint 6fEuaENy9uqhGirFsgcr5nHCNNDAy4LcsnqFr2zaHvJE 1000 --url devnet

Minting 1000 tokens
  Token: 6fEuaENy9uqhGirFsgcr5nHCNNDAy4LcsnqFr2zaHvJE
  Recipient: Exs22npoeZZNQEo2neCfKb57AtT3CSBVotZdySrEeZRD

Signature: 5aFxBv8ecmCLLukaR7fyGSXsZ9E7NwxRDrGwHNg2kCS9azV2fcNZku2dyiPYaYsWd9BUfTA94XmpaEpNU6y9p92R
```

```script
spl-token balance 6fEuaENy9uqhGirFsgcr5nHCNNDAy4LcsnqFr2zaHvJE --url devnet
1000
```

```script
spl-token supply 6fEuaENy9uqhGirFsgcr5nHCNNDAy4LcsnqFr2zaHvJE --url devnet
1000
```

```script
spl-token authorize 6fEuaENy9uqhGirFsgcr5nHCNNDAy4LcsnqFr2zaHvJE mint --disable --url devnet
Updating 6fEuaENy9uqhGirFsgcr5nHCNNDAy4LcsnqFr2zaHvJE
  Current mint: EMpjNXrJQ6AUENSMnqDSKAKewzod6Xbu4yBCMoTTij9t
  New mint: disabled

Signature: 2jdj87T21ZEfKQFMrfAi6Umwwab6PLsJTkTkXzJ5GzT2Vzahsdb4ZTTVYgpitxbupD59S4icwQBimbZ5PryxcuaW
```

```script
spl-token burn Exs22npoeZZNQEo2neCfKb57AtT3CSBVotZdySrEeZRD 500 --url devnet
Burn 500 tokens
  Source: Exs22npoeZZNQEo2neCfKb57AtT3CSBVotZdySrEeZRD

Signature: AiwUhProBvrYHUvoJNaXPP2enTwbJvthtwbafNKPszYwLEpZvD6S4xFqUnumzPWnE6z39d2cQduuqNdCLzBk8uL
```

Add token metadata:
6fEuaENy9uqhGirFsgcr5nHCNNDAy4LcsnqFr2zaHvJE
Continuous Yellow
YELLOW

## Solet

**Yes, it's a test wallet that nobody should use!**

_Be stupid at your own pace_

one annual pig hawk exercise leave donate upset table inhale stuff amazing keep prepare impulse master leader help winner prize stage luxury post load

---

https://www.youtube.com/watch?v=dmH2oPBk97w

https://github.com/jacobcreech/Token-Creator

https://github.com/WaqasAyubShah/SplToken

Solana Token List
https://github.com/solana-labs/token-list

Solana Rust - create token
https://medium.com/coinmonks/how-to-use-solana-token-spl-operations-using-rust-anchor-framework-d2c86fad8162

Solana Token extensions
https://solana.com/developers/guides/token-extensions/getting-started

Solana Cookbook
https://solanacookbook.com/gaming/interact-with-tokens.html#create-mint-and-burn-tokens-with-anchor
