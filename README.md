# Demo video: [Click here](https://www.youtube.com/watch?v=K2muOrjytyk)

# CRDFND

[CRDFND is a crowdfunding Dapp which is live on Polygon Mainnet!]()

## Project Description!

This is crowdfunding application where the backend is an polygon smart contract, and the frontend is an application hosted vercel. This creates a completely decentralized crowdfunding app with a verifiable and immutably published project plan.

Current crowdfunding platforms have a problem. Creators ask for funds to complete a project, but once funded, we don’t always see the expected results. This new crowdfunding app should work to prevent this.

The creator asking for funds sets a deadline for raising 100% of the funds. The funds are split into creator-defined batches, with each batch being linked to a milestone. If the full amount isn't raised, the balance is refunded to the project backers.

### Once fully funded, the project starts:

- The first batch of funds is released to the creator to start the project.

- If a majority of backers are unsatisfied with the progress, they can then vote to suspend the project, stop future payouts, and return the remaining funds to the backers. If completed, the next batch is released to the creator.

- The same rules are followed until all milestones are completed, and all funds have been distributed, or until backers vote to suspend the project.

### Steps to run this locally

1) clone this repository
2) npm install sha3
3) npm install
4) add your private key in truffle-config.js (LINE NO 59)
5) RUN: truffle migrate --reset --network matic
6) npm run serve

app starts at: http://localhost:8080
