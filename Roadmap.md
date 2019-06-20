# Boomerang Roadmap


## Short Term
### Token Sale?
In order to continue development and further fund the project we need to get our token sale out the door asap. There isn't a lot that needs to be done in order to launch a token sale technically, but Adam may have more concerns roadblocks on this.

### Integrate with Portis, Fortmatic, or Torus
In the begining we need a uniform way for a user to login to Boomerang. We can't use metamask because it is independent across different browser sessions so we would have no way of letting businesses know which public Ethereum address lines up with what customer. Torus gives us the best security guaruntees, but Portis is the most feature complete.

### Create a database which matches email -> public address
If we go with Portis, then every user that signs up on our website will have a public address matched to whichever email they signed up with. We need our own database that connects Address -> Email on first login.

### Create API which takes in tx signature and user email to send out review
Once we have a database with emails connected to public etheruem addresses, a business would simply need to call our api with the user's boomerang email and they could send out a review.

### Edit Smart Contracts to allow for use with the Gas Stations Network
In order to improve the UX for the customers, Boomerang should integrate the gas stations network into our smart contracts. This way users will not need gas to pay for submitting reviews. This is currently blocked by the Gas Stations Network mainnet release (which will release shortly), but the contracts can be written as such now.

### Clean up UI


## Medium Term
### Hire Designer to update website design and logos
Right now the website is thrown together with semantic react ui library, we could really use the eye of a designer to go over the website and improve the design.

### Find integration partner to hook up into flow
We need to find an integration partner to hook this flow up to ASAP in order to find pain points and determine long term strategy for developing new integration partners and easier flows.

## Long Term
### Create mobile app that can push notifications to user
The most ideal flow in my opionion for future sign ups is:
Business emails user to download boomerang and hit submit when their down(based on business's email on record with user)
User downloads Boomerang mobile app (and we put public key/email pairing into our databased)
User hits submit in email.
~2 mins later user receives a push notification with a new review from business.


### Create workflow for business to add offerings to repeat customers
Right now there is the idea of XP that users and workers can earn for completing reviews and receiving positive reviews, but there is not way on-chain to release an offering based on that XP score.

### Multi-sig contract wallets with ENS names (Universal Login)

