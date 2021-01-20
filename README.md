

This repo contains a translation of the protocol specification originally written in TLA<sup>+</sup>, to the language of [Electrum](http://haslab.github.io/Electrum/)(a temporal logic extension of [Alloy](https://alloytools.org/)).

The 3 models presented are:
* **Consensus** - specifies the meaning of Consensus. At some point a value is chosen and that value remains chosen forever.
* **Voting** - a high level specification of the protocol where nodes can either vote for some value, or skip votes in some ballots.
* **Paxos** - this specification introduces messages and the 4 phases of the protocol.



