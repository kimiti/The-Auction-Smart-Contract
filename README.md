## The-Auction-Smart-Contract

### Smart contract for a decentralized Auction, an ebay alternative;

- the auction has:
  -An owner(the person that sells the goods and services)
  -A start and an end

- the owner can cancel the auction if there is an emergency and can finalize the auction after its end time

- people send ether when calling placebid()function the address is registered a map { sender address and the value}

- users are incentivised to bid the mximum they're willing to pay, but they are not bound to that full amount ,but rather to the prevoius highest bid plus the increment.

- the highest binding bid is the selling price and the highestBidder the person who won the auction

- after the acution ends the owner gets the highest binding bid and everybody else withdraws their sent amount
