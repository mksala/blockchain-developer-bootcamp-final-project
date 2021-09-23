# Digital Safe
This project is about setting the foundations for specialized data storage on blockchain. It needs to be both secure and convenient.
## Objective 1
Specifically at first, we focus on storing and sharing private keys in an attempt to help with inheritance procedures still immature within crypto industry to this day.

## Problem
In a world of digital currencies and identities for everything, preserving the data that provides access to these has never been so important. While there are custody services and other third parties offering such features, we have yet to see a safe and convenient trustless application providing the same services. There is an essential need for this type of dApp that will only grow over time. 

## Proposed Solution
Provide the interface and functionalities needed to store essential and private data on the most dencetralized and secure platforms that exist, namely Ethereum for smart contracts (storage of reference links only), and IPFS for larger storage.

As part of the storing and viewing mechanisms, the aim is to provide capabilities for the user to share any of its data to other Ethereum accounts.

A lot more advanced features are planned for later stages of the dApp.

## User Flow
### Phase one with Academy
- Web3 sign-in and a simple text box will invite the user to input his text message, with no enforced validation as to offer flexibility in the type of private key or secret that needs to be stored, except for a conservative limit of character numbers.
- The data is then stored in IPFS, while the hash returned from this is stored in Ethereum
- The user can view all his stored messages when connected to the respective wallet. 
- An option to share one or all the messages is available for the user.Proceeding with this functionality will provide unencrypted reading accesss to the specified Ethereum account(s).
### Phase two in the future
- Automatically share/send the password with a specified email if the message was not read for more than 3 months / 3 years  or other specified timeframe.
- Make the time before sharing configurable (not for the admin, but configurable for the user who inputs the message).
- This heritage capability would be an option for the user when submitting a post. If selected, he would have to define a timeframe before heritance is triggered. 


## Notes & TBD
- At this stage, Ethereum blockchain is used for the storing of the IPFS hash. However research should be ongoing for the eventual addition of other public blockchains and content storing mechanisms such as Arweave.
