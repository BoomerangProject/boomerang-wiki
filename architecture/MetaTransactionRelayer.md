![Boomerang Logo](https://github.com/BoomerangProject/boomerang-wiki/blob/master/images/logo.png "Boomerang Logo")
# Meta Transaction Relayer
Boomerang, in order to provide a more familiar User Experience (UX), will utilize the concept of [Meta Transactions by Austin Thomas Griffith](https://medium.com/@austin_48503/ethereum-meta-transactions-90ccf0859e84).
Meta Transactions allow a third party to pay the gas costs for a user. In addition, the user can offer up an ERC-20 token reward in order to
incentivize the third party to execute a transaction on behalf of the user. This will allow a user to interact with a DApp without ever needing to know about
Ethereum or Gas. 

Boomerang will use [EthWorks Universal Login Relayer](https://github.com/EthWorks/UniversalLoginSDK/tree/master/universal-login-relayer) to relay Meta-Transactions. The user will pay a fee in BOOM tokens to submit review requests and to submit reviews.
