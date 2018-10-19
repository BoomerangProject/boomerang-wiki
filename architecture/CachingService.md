![Boomerang Logo](https://github.com/BoomerangProject/boomerang-wiki/blob/master/images/logo.png "Boomerang Logo")
# Caching Service
In order to provide data quickly to the react app, a caching service will need to be built. Contained is the proposed architecture for such a service.

### Caching Server
The Caching Server will periodically query Boomerang's Ethereum full node for new 'ReviewRequested' events on the Boomerang Smart Contract.
When a new event is found, the Caching Server will check an S3 bucket to see if the Event Transaction Hash has already been recorded.
If it has not been recorded, the Caching server will update the user information in DynamoDB based on the new events recorded.

More information to come...
