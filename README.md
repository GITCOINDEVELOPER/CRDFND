# Demo video: [Click here](https://www.youtube.com/watch?v=K2muOrjytyk)
# Test project transaction hash: [Click here](https://polygonscan.com/tx/0xb3cb5cc43aeec7f8038b37c581e0a0d016186145d9eabca758252b096b2c8df1)

# CRDFND

CRDFND is a crowdfunding Dapp which is live on Polygon Mainnet!

## Project Description!

This is crowdfunding application where the backend is an polygon smart contract, and the frontend is an application script. This creates a completely decentralized crowdfunding app with a verifiable and immutably published project plan.

Current crowdfunding platforms have a problem. Creators ask for funds to complete a project, but once funded, we don’t always see the expected results. This new crowdfunding app should work to prevent this.

The creator asking for funds sets a deadline for raising 100% of the funds. The funds are split into creator-defined batches, with each batch being linked to a milestone. If the full amount isn't raised, the balance is refunded to the project backers.

### Once fully funded, the project starts:

- The first batch of funds is released to the creator to start the project.

- If a majority of backers are unsatisfied with the progress, they can then vote to suspend the project, stop future payouts, and return the remaining funds to the backers. If completed, the next batch is released to the creator.

- The same rules are followed until all milestones are completed, and all funds have been distributed, or until backers vote to suspend the project.

### Steps to run this locally

1) clone this repository
2) yarn
3) add your private key in truffle-config.js (LINE NO 59)
4) RUN: truffle migrate --reset --network matic
5) npm run serve

app starts at: http://localhost:8080
