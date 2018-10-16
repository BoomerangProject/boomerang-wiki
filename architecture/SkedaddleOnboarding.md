# Skedaddle Onboarding / Business Integration
![Skedaddle + Boomerang Logo](https://github.com/BoomerangProject/boomerang-wiki/blob/master/architecture/imgs/boomsked.png "Skedaddle + Boomerang Logo")
## Proposed Solution
1. Skedaddle creates a store of deployed identity contracts pre-loaded with some amount of Boom token (~$5-10)
2. User orders a bus, is asked to write a review
3. A pre-loaded identity contract writes the review on the user's behalf (through Skedaddle using the BoomerangSDK)
4. User is given a recovery key and prompted to join Boomerang to claim Boom reward by logging in with recovery key.
> Example Recovery Key: 'zeizod-ahe-jo-joffar-luvapi'
5. User logs into identity through Boomerang react app.
6. Boomerang and Skedaddle welcome user, and asks for a few more steps to claim reward.
7. Boomerang prompts user to accept or remove Skedaddle Central Account recovery (pros and cons list)
8. Boomerang prompts user to remove old recovery key, and generate a new one, and put it somewhere safe. (Can't continue until new code generated)
9. User owns and is logged into a Boomerang account pre-loaded with Boom tokens.


   
