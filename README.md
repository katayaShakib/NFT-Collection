# NFT-Collection

There are a total of 20 Crypto Devs NFTs that can ever exist.

User's are allowed to mint only 1 NFT with one transaction.

Whitelisted users, are able to mint a NFT for free.

Other users need to pay 0.01 ETH to mint the NFT.

Have deleted the front-end since this is a simple enough contract.

You can simply tinker with the contract by minting NFTs through Etherscan, as I have verified the contract on it.

Go to https://sepolia.etherscan.io/ and search up my contract address "0x96B091A0c0235846Daac59301bC16A6f7e43C9bf", and go to the Contract tab and then Write Contract.

Connect your wallet to Etherscan, and then call the mint function.
You will notice that Etherscan expects you to write down a payableAmount in Ether. Since I marked our mint function payable, You can attach ETH along with the transaction. However, if you are whitelisted, you don't need to pay to mint the NFT!

Input payableAmount as 0, and then click on Write. Confirm the transaction and watch it go through, and you will end up with a new NFT on Sepolia!

Now, if you try doing the mint again without 0 as payableAmount, you will see that the transaction will actually fail!

To mint another NFT with the same account, or with a different account in your wallet, one that was not whitelisted previously, you need to change payableAmount to be 0.01 and then press Write, the transaction will go through because now you're paying the price of the NFT!