# SampleSolidityDEX
Basic decentralized exchange smart contract written in Solidity. Users can deposit, trade, and withdraw tokens. 
It's important to note that this smart contract is just a basic example and is not production ready. It should not be used in a real world scenario without proper testing and security audits.

This contract allows users to deposit and withdraw tokens, as well as trade them. The balanceOf mapping keeps track of the token balance for each user and token. The deposit function accepts ether and adds it to the msg.sender balance. The withdraw function transfers the specified amount of a token from the msg.sender balance to the msg.sender's address. The trade function allows a user to trade one token for another by transferring a specified amount of one token from their balance and adding the same amount of the other token to their balance.
