# Boom Tokens
A [Customer](https://github.com/BoomerangProject/boomerang-wiki/blob/master/architecture/UserTypes.md) will receive Boom tokens from a [Business](https://github.com/BoomerangProject/boomerang-wiki/blob/master/architecture/UserTypes.md) in return for submitting a rating and review. The number of tokens the Customer receives will depend on the settings used by the Business. If the Business is using the Boomerang SDK, the Customer will also receive a bonus number of Boom tokens based on their level (see below).

Boomerang ratings operate on a three-point scale (negative, neutral, and positive). A [Worker](https://github.com/BoomerangProject/boomerang-wiki/blob/master/architecture/UserTypes.md) will receive Boom tokens from a Business based on the review they received from a Customer. As with Customer rewards, the number of tokens the Worker receives will depend on the settings used by the Business.

# Experience Points
We expect that Workers will earn more Boom tokens than Customers because a single Worker will likely be involved in more transactions (and thus receive more Customer reviews) in a single day than a Customer will make purchases (and thus submit more reviews). To make participation more valuable to Customers, Boomerang will reward Customers with experience points for each rating and review submission. As with Boom token rewards, the amount of experience points that the Customer receives for a rating and review will be set by the Business. As we add additional businesses to Boomerang, we will explore the impact of aggregating experience points by source Business and its impact on levels and Boom token rewards. 

# Levels
A level is a threshold where the Customer has earned a set number of experience points. For each new level, the Customer will get an increasing amount in bonus Boom tokens for their rating and review from those Business that use the Boomerang SDK. The Boomerang SDK will support ten levels; a Business will be able to customize the bonus modifier for each level.

# Using Rewards
