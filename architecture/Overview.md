![Boomerang Logo](https://github.com/BoomerangProject/boomerang-wiki/blob/master/images/logo.png "Boomerang Logo")
# Boomerang Architecture Overview
Boomerang will implement a [Universal Login](https://github.com/BoomerangProject/boomerang-wiki/blob/master/architecture/UniversalLogin.md) which will make use of a [Metatransaction Relayer](https://github.com/BoomerangProject/boomerang-wiki/blob/master/architecture/MetaTransactionRelayer.md) in order to create a seamless user expierence that mirrors the typical flow of a Web 2.0 Application.

In addition, Boomerang will develop the [BoomerangSDK]() for our [Boomerang React App]() and for [Businesses](https://github.com/BoomerangProject/boomerang-wiki/blob/master/architecture/BusinessIntegration.md) to use in order to request reviews, and retreive historical reviews, ratings, and experience levels.

To support the BoomerangSDK, the Boomerang Foundation will build an [Event Caching Layer](https://github.com/BoomerangProject/boomerang-wiki/blob/master/architecture/CachingService.md) that will serve data more rapidly to the BoomerangSDK through [BoomerandAPIs]() rather than querying an Ethereum full node, and will allow the user to interact with the DApp without a web3 provider.

The [Boomerang Smart Contracts]() allow businesses to submit review request, and allow users to submit reviews about a worker or business, and the [Boomerang Reward System]() will be built off of the information that the contract's events log.

As part of integration with Boomerang, Skedaddle will create an [Identity Provisioning Service]() which will give identities to new users and an [Identity Recovery Service]() which will act as an optional central recovery service for Skedaddle users who misplace backup codes or lose access to their devices.

![Boomerang Architecture](imgs/BoomerangArchitecture.jpg "Boomerang Architecture Diagram")
