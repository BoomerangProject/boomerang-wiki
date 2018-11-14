# Boom Tokens
A [Customer](https://github.com/BoomerangProject/boomerang-wiki/blob/master/architecture/UserTypes.md) will receive Boom tokens from a [Business](https://github.com/BoomerangProject/boomerang-wiki/blob/master/architecture/UserTypes.md) in return for submitting a rating and review. The number of tokens the Customer receives will depend on the settings used by the Business. If the Business is using the Boomerang SDK, the Customer will also receive a bonus number of Boom tokens based on their level (see below).

Boomerang ratings operate on a three-point scale (negative, neutral, and positive). A [Worker](https://github.com/BoomerangProject/boomerang-wiki/blob/master/architecture/UserTypes.md) will receive Boom tokens from a Business based on the review they received from a Customer. As with Customer rewards, the number of tokens the Worker receives will depend on the settings used by the Business.

# Experience Points
We expect that Workers will earn more Boom tokens than Customers because a single Worker will likely be involved in more transactions (and thus receive more Customer reviews) in a single day than a Customer will make purchases (and thus submit more reviews). To make participation more valuable to Customers, Boomerang will reward Customers with experience points for each rating and review submission. As with Boom token rewards, the amount of experience points that the Customer receives for a rating and review will be set by the Business. As we add additional businesses to Boomerang, we'll explore the impact of aggregating experience points by source Business and its impact on levels and Boom token rewards. 

# Levels
A level is a threshold where the Customer has earned a set number of experience points. For each new level, the Customer will get an increasing amount in bonus Boom tokens for their rating and review from those Business that use the Boomerang SDK. The Boomerang SDK will support ten levels; a Business will be able to customize the bonus modifier for each level.

# Using Rewards
Customers will have two ways to use their Booms:
1. Send them to a cryptocurrency exchange and sell them for other crypto or fiat currencies.
2. Send them to a Business in exchange for full or partial discounts on products and services. 

For the second option, we plan to give Businesses the capability of setting up loyalty programs where they can specify the details of the offer and the amount of Booms required to obtain the offer. Businesses will want to set up loyalty programs as a way to recoup Boom tokens at a cost lower than what they'd pay for them on an exchange and as a way to get return visits from Customers. As we add additional businesses to Boomerang, we'll explore loyalty program options that are limited to Customers who have previously made a purchase with the Business.

Activation of the offer will take place either in the Boomerang dApp, or through a whitelabeled "Pay With Booms" feature on the Business's website or app. Transfers of Boom tokens from the Customer's identity to the Business's identity would take place within Boomerang, but it would be the responsibility of the Business to execute on the promised offer. 

In addition to their options as a Customer user, Workers will have the option of sending Boom tokens to a Business they work for in exchange for payments of currency outside of Boomerang. The interface for this exchange will be similar to that offered to Customers: the Business will create offers for how much and what type(s) of currency they will offer for Booms, which the Worker will be able to access through the dApp. The programs will be helpful to both parties: Businesses will recoup Boom tokens at a lower cost than market, while Workers will be able to turn their Booms into cash without needing to know how to use exchanges.
