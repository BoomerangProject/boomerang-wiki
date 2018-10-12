![Boomerang Logo](https://github.com/BoomerangProject/boomerang-wiki/blob/master/images/logo.png "Boomerang Logo")
# Boomerang Architecture Overview
Boomerang will implement a [Universal Login](https://github.com/BoomerangProject/boomerang-wiki/blob/master/architecture/UniversalLogin.md) which will make use of a [Metatransaction Relayer](https://github.com/BoomerangProject/boomerang-wiki/blob/master/architecture/MetaTransactionRelayer.md) in order to create a seamless user expierence that mirrors the typical flow of a Web 2.0 Application.

In addition, Boomerang will develop the [BoomerangSDK]() for our [Boomerang React App]() and for [Businesses](https://github.com/BoomerangProject/boomerang-wiki/blob/master/architecture/BusinessIntegration.md) to use in order to request reviews, and retreive historical reviews, ratings, and experience levels.

To support the BoomerangSDK, our project will build a [Event Caching Layer]() that will serve data more rapidly to the BoomerangSDK than querying an Ethereum full node, and will allow the user to interact with the DApp without a web3 provider.

Boomerang will create the [Boomerang Login Service]() which will act as an optional central recovery service for users who misplace backup codes or lose access to their devices.

The [Boomerang Smart Contracts]() allow businesses to submit review request, and allow users to submit reviews about a worker or business, and the [Boomerang Reward System]() will be built off of the information that the contract's events log.


![Boomerang Architecture](imgs/BoomerangArchitecture.jpg "Boomerang Architecture Diagram")
