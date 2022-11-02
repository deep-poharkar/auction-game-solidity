# dollar-auction.sol

> A dollar auction implementation in Solidity

A dollar auction is a [non-zero sum sequential game], where you auction some amount of currency higher than the minimum bid, and keep the two highest bids (the first one wins, but the second one doesn't get refunded).

This presents a scenario where, even after the highest bid exceeds the prize, the only way for the second highest bidder to cut their losses is to continue bidding.
