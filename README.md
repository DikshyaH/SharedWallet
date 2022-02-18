# SharedWallet
A smart contract which functions like a shared wallet where you can deposit and transfer Ethereum 

On deploying the contract, the address that deploys is automatically set as the Owner.
Only the owner is allowed to add members for the wallet along with an allowance for each member.
Only the members are allowed to withdraw money from the wallet based on the allowance set by the Owner. 
Any address is allowed to deposit money to the wallet.

Ive also imported Ownable contract from OpenZepplin

Had written this solidity code for fun :)
