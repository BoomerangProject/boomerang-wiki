![alt text](https://github.com/BoomerangProject/boomerang-wiki/blob/master/images/logo.png "Boomerang Logo")
# October 2018 Meeting Notes

### Team Sync-Up 10/01/2018
To summarize what Kyle, Garin, and Eric just discussed: we reviewed the proposed [rating and review flow](https://www.lucidchart.com/invitations/accept/1ba58674-ea34-4e06-a0da-9d424039df6a). In addition, Kyle is now working directly with two Polish developers who are also working on Universal Login to avoid duplication of effort. The goal is to have a working prototype in place by the end of the month for the Ethereum Developer's Conference, followed by internal work to combine the prototype with Boomerang smart contracts.

### Update 10/03/2018
Kyle has been working on the open source [UniversalLoginSDK's backup code generator](https://github.com/EthWorks/UniversalLoginSDK/pull/81)

### Update 10/08/2018
Kyle has finished [UniversalLoginSDK's backup code generator](https://github.com/EthWorks/UniversalLoginSDK/commit/66f35765eed07ca874442322de30ebdefdc8ba33) and has begun work on [private key storage](https://github.com/EthWorks/UniversalLoginSDK/issues/93)


### Update 10/10/2018
Kyle has submitted a [pull request](https://github.com/EthWorks/UniversalLoginSDK/pull/103) for local private key storage.

Kyle and Eric discussed the state of the Universal Login SDK and launch plans for Boomerang. As of today, the plan is to complete the SDK PoC by the end of DevCon, refactor the Boomerang Smart Contracts to fix any compatibility issues with the SDK in November, integrate the Smart Contracts into the POC in December and January, creating a pre-Alpha version where users can create Customer accounts, submit reviews of one Worker account and one Business account, and receive rewards from a testnet. We would consider inducements like a launch bonus of Booms to get users to test this pre-Alpha. 
1. **October**:
Kyle will continue to work on [UniversalLoginSDK](https://github.com/EthWorks/UniversalLoginSDK), which will be featured in Prague during [devcon4](https://devcon4.ethereum.org/) at the end of the month.
2. **November**:
Kyle, Eric, and Garin will review how Boomerang rewards are structured, based on our discussions, Kyle will refactor the Boomerang contracts to match the vision and it will be documented in the wiki.
3. **December - January**:
Kyle and other developer resources at Skedaddle will begin integrating the Boomerang smart contracts into the [UniversalLoginSDK](https://github.com/EthWorks/UniversalLoginSDK) example project and refactor as needed. This will be the Alpha product.

### Update 10/12/2018
Kyle has re-written the Boomerang platform into a single [smart contract](https://github.com/BoomerangProject/boomerang-contracts/blob/master/Boomerang.sol) by extracting the reward system.
Kyle has updated wiki with a more thorough [architecture overview and diagram](https://github.com/BoomerangProject/boomerang-wiki/blob/master/architecture/Overview.md)

### Update 10/15/2018
Kyle has been updating the wiki with additional information about the complete Boomerang architecture. Kyle is continuting to work on [persistent storage](https://github.com/EthWorks/UniversalLoginSDK/pull/103) for the UniversalLoginSDK

### Update 10/17/2018
Kyle has been updating the wiki with additional information about the complete Boomerang architecture. Kyle has created a proposed [integration plan](https://github.com/BoomerangProject/boomerang-wiki/blob/master/architecture/SkedaddleOnboarding.md) for Skedaddle + Boomerang. Kyle created the [Boomerang2.0 monorepo](https://github.com/BoomerangProject/boomerang2.0) where the BoomerangSDK, Boomerang mobile and desktop app will live. Kyle updated the [Boomerang Contract](https://github.com/BoomerangProject/boomerang-contracts/blob/master/contracts/Boomerang.sol) to contain store user xp data. Kyle will work to turn the new Boomerang Contract project into a more standard truffle project.

### Architecture Walkthrough Notes 10/17/18
Simon proposed a giving a qr code to the user which contains the one-time access code and username of the user to make it easier to login to boomerang: Example (boomerang://setup?id=abc.xyz&access_key=abc123)

### Update 10/19/18
Kyle has been working on the [boomerang-contracts](https://github.com/BoomerangProject/boomerang/tree/master/boomerang-contracts) project, adding tests using the waffle library. Kyle talked with John, Simon, and Kinan about the roadmap in terms of engineering resources. Kyle will continue writing tests and making our smart contracts audit-ready for November.

### Update 10/22/18
Kyle has been working on fleshing out and hooking together the [boomerang monorepo](https://github.com/BoomerangProject/boomerang/tree/master/boomerang).
