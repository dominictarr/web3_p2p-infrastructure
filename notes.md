
# one liner

convince ethereum that consistency for everything is holding them back

consistency is only useful when you actually need consistency.
for everything else it is too expensive.

therefore avoid consistency when possible

ssb can be everything except a currency

# overview

* about me (scuttlebutt, auditing)

* what is scuttlebutt?

  * many interlinked private blockchains (feeds) (each owned/authored by 1, replicated by many)
  * only replicate as many feeds as relavant. overlapping partial replication.
  * lean on social patterns
    * small world network
    * likely to have mutual friends and interests
    * lean on pre-existing incentives

* use-value
  * graph of eth price.
    compare value (usefulness) and speculation (hype)

* how to get use-value:
  start with usable software and use it your self
  sell a solution, or something fun, not an abstract vision

* scuttlebutt and dat (utility focused)

* everything has social patterns, even if not a social network.
  for example lightning network

---

idea for a generic scuttlebutt-ethereum application

* use evm for transactions, minimize scope of transaction
* use ssb for moving data.

* basic dapp is a market (of some kind)
  * any market has a lot of _information_
    * what is for sale, who is selling it, what price etc
    * too much data for contract, also iterating over it is too expensive

  * all contract ops should be O(1)
  * contract is like hardware, don't change it, so make it as simple as possible.

  * eventually consistent p2p is easy to change.
    everything is a softfork. update this not eth contracts.
---
