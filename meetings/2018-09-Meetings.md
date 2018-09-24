![alt text](https://github.com/BoomerangProject/boomerang-wiki/blob/master/images/logo.png "Boomerang Logo")
# September 2018 Meeting Notes

### Engineering Standup 9/14/2018
Discussed Universal Login and Metatransactions with how they relate to Boomerang. Ben built out [alpha APIs in GoLang](https://github.com/BoomerangProject/boomerang-api) which will be used by the Boomerang DApp. Kyle has been working on the [High Level Design of Boomerang Universal Login](https://github.com/BoomerangProject/boomerang-wiki/blob/master/architecture/UniversalLogin.md) and fleshing out the Boomerang Wiki.

### User Login Design Meeting 9/14/2018
Garin, Ben, Eric, and Kyle discussed what the user login flow might look like with Boomerang Universal Login.

Deliverables: [Garin's Login Screens](https://github.com/BoomerangProject/boomerang-wiki/blob/master/architecture/documents/Boomerang_web_signup-login_flow.pdf), [Eric's Login Flow Diagram](https://github.com/BoomerangProject/boomerang-wiki/blob/master/architecture/imgs/BoomerangSignInFlows.png)


### Engineering Standup 9/17/2018
Kyle and Ben discussed updated roadmap and had a short discussion about how integration with Skedaddle might operate. Ben and Kyle are continuing to do research into Universal Login and Metatransactions. Kyle is continuing to flesh out the Boomerang Wiki and will start on a [Universal Login proof-of-concept.](https://github.com/BoomerangProject/boomerang-universal-login) 


**Suggested Roadmap:**


September 2018 - December 2018

- Build architecture for Universal Logins
- Build Metatransaction Layer
- Build ENS subdomain registrar
- Release alpha smart contracts on testnet
- Deploy limited release of alpha dapp

January 2019 - May 2019

- Have smart contracts audited by security professionals
- Release contracts to Mainnet
- Beta integration with Skedaddle platform
- Deploy limited release of beta dapp (releases for iphone, android, and web client)
- Onboard Skedaddle riders and drivers onto beta platform

June 2019 - December 2019

- Launch iOS app to Apple App Store
- Launch Boomerang Foundation website with quickstart documentation
- Launch android library to JCenter for easy gradle integration
- Launch iOS library to CocaoPods for easy Xcode integration
- Launch android app to Google Play Store

### Engineering Standup 9/18/2018
Kyle and Ben have been researching and determining the details behind Boomerang's Universal Login. We found a [github repository](https://github.com/EthWorks/EthereumIdentitySDK) which gives us some base functionality for Universal Login. We will use this project to bootstrap the [Boomerang Universal Login Proof of Concept](https://github.com/BoomerangProject/boomerang-universal-login).

### Engineering Standup 9/19/2018
Kyle and Ben are continuing to poke at the [EthereumIdentitySDK](https://github.com/EthWorks/EthereumIdentitySDK) repo while making changes to our own proof of concept. Discussed difficulties with storing an email in an eth domain space (specifically around the use of dots in email). 

### Engineering Standup 9/20/2018
Kyle has been picking out pieces of the [EthereumIdentitySDK](https://github.com/EthWorks/EthereumIdentitySDK) and plugging in boomerang specific pieces. Yesterday he add a username generation to map to email addresses so that users can log in with an email. 

Ben has been testing the assumptions we have made using EthereumIdentitySDK, ensuring that the identity contract, relayer, and clicker contract are working as expected behind the scenes. 

Kyle and Ben discussed Boomerang's reward structure and how users and workers can accumulate boom through reviews and how businesses can set up a reward structure for it's workers and users. We discussed a potential verbage shift - will discuss further with Garin when he is in Boston next week.

Kyle and Ben discussed [metatransaction standards](https://github.com/austintgriffith/meta-transaction-format-share) which are currently being discussed and created by a community of ethereum developers. This also includes the concepts behind a Metatransaction Relayer Pool which Boomerang can eventually make use of.

###  Work Notes 9/21/2018
Kyle has continued to poke at the [Boomerang Universal Login Proof of Concept](https://github.com/BoomerangProject/boomerang-universal-login) while merging in changes from its parent fork.

###  Work Notes 9/24/2018
Kyle has continued to poke at the [Boomerang Universal Login Proof of Concept](https://github.com/BoomerangProject/boomerang-universal-login) while merging in changes from its parent fork. 

Kyle will be working on a [presentation](https://docs.google.com/presentation/d/175IATallX1G-9yTQFhMQWhWqOr9UcuPajqJBsdA9G4Y/edit?usp=sharing) for Skedaddle about the progress of Boomerang and its current vision.

Kyle has been in contact with some other teams working on MetaTransactions and will take part in the first [MetaTx Community Call](https://hackmd.io/-fF2VKIFRzyiWaxVQAh0wA?view) on Thursday @ 11am.




