# OpenSquare: a collaboration network in web3 environment

## Abstract
Blockchain brings transparency and irreversibility which will be important in collaboration based credit building. We will build a collaboration platform which
facilitates collaborations between users and store the corresponding data to blockchain. The stored onchain objective and subjective data will be used to build users' credit
model. Finally, we will build a collaboration network which helps users in the following ways.
- Platforms which support collaborations like bounties, paid questions, etc.
- A profile site where users can manage their profiles with their keys
  - Onchain data will be aggregated for users
  - Credit model will be built based on the on-chain collaboration data

## Collaborations
### Why
We build collaborations in the web3 environment first with following thoughts.
- Blockchain based collaborations solve problems in web2.
  - Payment: crypto fund can be locked by code, while it provides a more reasonable way to handle the fund issues, especially the trust.
  - Relatively more trusted history records. Collaborators can check each other's collaboration history more easily, and the records are more credible.
- Users' credit model dimension will be composed of different indicators. Currently, most onchain transactions
and even DeFi behaviors are not enough to build credit which benefit users building collaborations.
  
### What
The planned collaboration platform will solve concrete problems.
- Bounties platform. It will help projects build their products with more builders and lower cost, and builders earn crypto with their abilities.
- Paid question/topic platform. Crypto world evolves with new knowledge, ideas and products, and this platform will help collaborators share the information in a more effective way.

Collaborations are actually behaviors of trading for labor and ideas. There will be many requirements for different collaboration ways, and the direction is building many collaboration components/modules, so users can compose them to support their business. 

#### How
We will first support collaborations between projects(B side) and builders(C side). To gain trust from and build connections with the target projects, we will do following steps:
1. Build common goods like explorers, governance tools for these projects.
2. Lead some projects' ecosystem building as curators.
3. Build platforms where projects and builders can join the collaboration network by themselves.

## Credit building
People’s credit can usually be judged by their behaviors. We can classify on-chain behaviors into two categories, objective ones and subjective ones.
- Objective behaviors are related with the predefined rules, like breaking/committing promises.
- Subjective behaviors are remarks one collaborator gave to another.

To help users’ usage in various scenarios, we build users’ credit score in three ways, behavior score, general score and feature score.

- Behavior score. It’s built directly from users’ collaboration activities. Usually one behavior has a score range which will be applied to the user’s score, and this score range can be governed with OpenSquare tokens.
- General score. It’s just a normalization of behavior score which may help users’ understanding and comparison.
- Feature score. Different behaviors may reflect different human traits. Category of different behaviors and the corresponding credit building will help users’ know another one’s different trait.

## Trusted profile
Profile trustworthiness can be enhanced by blockchain in the following ways.
- History behaviors stored on-chain will be aggregated.
- Users’ profiles can be bonded by partners with asset reservation.

In the OpenSquare network, we stored the collaboration data which contain the subjective and objective ones to blockchain or IPFS. OpenSquare’s profile solution will support the following features.
- Users can edit their profile and corresponding proof will be stored to blockchain or IPFS.
- User on-chain behavior data will be aggregated and shown together with the provided info.
- Users bond each other with asset reservation while reservation may be slashed due to misbehavior.
- Different user roles will be supported. Special features will be provided to enterprise users.
- Credit model will be built based on the profile's subjective and objective data.
