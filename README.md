# lottery
This is a simple lottery contract implemented in Solidity. The contract allows players to participate by sending 1 ether to the contract address. The manager, who deployed the contract, can initiate the winner selection process when there are at least three players. The winner is chosen randomly using a hash of block difficulty, timestamp, and the number of players. The contract transfers the entire contract balance to the winner and resets the list of players for the next round.
