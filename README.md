# voting-app

A study to understand how blockchain applications work for future projects.
I followed this tutorial to get it done [The ultimate ethereum dapp project](https://www.dappuniversity.com/articles/the-ultimate-ethereum-dapp-tutorial).
What I discovered is that deploying code to the ethereum network is a bit worrysome because your functions are public and if you introduce bugs to your code it's difficult to rollback those functions.
Since voter information is hidden. That is the whole premise of blockchain technology. It's hard to enforce rules without running some external database that validates that the address given is for a registered voter.
If better technologies pop up that make development easier for blockchain I might give it another swing.

## Running this project

You will need metamask on your browser, ganache and truffle to be able to run this project.

To run this project have ganache running on the background and then run this command

```
truffle migrate
```

Then you will need to point metamask to your local ganashe server. After you accomplish that you will be able to vote
