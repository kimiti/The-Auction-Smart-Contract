## The-Auction-Smart-Contract

### Smart contract for a decentralized auction, an ebay alternative

the auction has: an owner(the person that sells goods and services) a start and an end

the owner can cancel the auction if there is an emergency and can finalize the auction after its end time

people send ether when calling function placebid() we will register in mapping the sender address and the value

the highestbiddingbid is the selling price and the highestBidder the person who won the auction

after the acution ends the owner gets the highesbiddingbid and everybody else withdraws their sent amount
