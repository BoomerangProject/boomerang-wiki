![alt text](https://github.com/BoomerangProject/boomerang-wiki/blob/master/images/logo.png "Boomerang Logo")
# Boomerang Universal Login
The Boomerang project plans to implement [EIP 1078: Universal Login by Alex Van de Sande.](https://eips.ethereum.org/EIPS/eip-1078)
This EIP describes a method of creating an "Identity" for the user (a contract on the Ethereum Blockchain) in which 
each user device is capable of being an "accessor" to this contract and the user can add new devices or "accessors" in
order to access their account with different devices. This is done by storing a private key on the user's device that 
has permissions on the identity contract. Each device will contain its own private key. The identity contract of the 
user will have an ENS (Ethereum Name Service) subdomain associated with the contract. For example, Bob may create an 
identity with Boomerang and the subdomain bob.boomerang.eth would be associated with his identity.

#### Terms
* **UWoB** - User, Worker, or Business
* **ICS** - Identity Creation Service

![alt text](imgs/BoomerangUniversalLogin.jpg "Boomerang Universal Login Architecture Diagram")


### Creating an Identity through Boomerang
The Boomerang Foundation, aiming to provide a familiar user experience to Web 2.0 Applications, will supply an Identity Creation Service (ICS) for Users, Workers, and Businesses who wish to interact with the Boomerang ecosystem. Through this service, a UWoB (User, Worker, or Business) will need to complete a verification process (TBD - could be email + phone or captcha) to prevent a spam attack on our Identity Creation Service. Part of this verification process will have the UWoB create login credentials. With these login credentials, a UWoB can request that Boomerang add a verified device (which has its own private/public key) to the identity contract. If a UWoB loses access to all of the devices which can access their identity, then they can use their login credentials in order to register a new device. To a UWoB this will be very familiar to a Web 2.0 application. However, it is important that the UWoB is able to opt-out of this service in order to take full advantage of a Web 3.0 DApp (Decentralized Application) in which the UWoB does not need to trust any centralized 3rd party in order to interact with the DApp.

#### Opting Out of Central Account Recovery
If a UWoB has used Boomerang's ICS  to create and Ethereum Identity, then they have the option of...

#### Spam Attacks on Boomerang's Identity Creation Service
Since The Boomerang Foundation will be paying the gas costs of creating identity contracts of UWoBs, it is vulnerable to spam attacks which would drain the funds of the Boomerang foundation, while giving the attacker a free Ethereum Identity with an associated ENS subdomain. With this in mind, it is important that Boomerang's ICS has a strong validation mechanism when onboarding new users. This validation mechanism is still to be determined.

### Logging in with an Existing Ethereum Identity
