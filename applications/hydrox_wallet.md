# W3F Grant Proposal

> This document will be part of the terms and conditions of your agreement and therefore needs to contain all the required information about the project. Don't remove any of the mandatory parts presented in bold letters or as headlines! Lines starting with a `>` (such as this one) can be removed.
>
> See the [Grants Program Process](https://github.com/w3f/Grants-Program/#pencil-process) on how to submit a proposal.

- **Project Name:** HydroX Wallet - MVP
- **Team Name:** Hydro Labs Inc.
- **Payment Address:** BTC, Ethereum (USDT/DAI) or Karura (kUSD) payment address. Please also specify the currency. (e.g. 0x8920... (DAI))
- **[Level](https://github.com/w3f/Grants-Program/tree/master#level_slider-levels):** 2

> ⚠️ *The combination of your GitHub account submitting the application and the payment address above will be your unique identifier during the program. Please keep them safe.*

## Project Overview :page_facing_up:
This application is in response to the [Socail Recovery Wallet RFP](https://github.com/w3f/Grants-Program/blob/master/rfps/social-recovery-wallet.md)

### Overview

HydroX Wallet is a Polkadot browser extension wallet. As the current ecosystem does not have an easy-to-use wallet, we are building an open-source user-friendly wallet that makes it safe and easy to send, receive, stake and swap on the Polkadot blockchains. The HydroX Wallet aims to support the evolution of the Polkadot DeFi community and provide an effortless UX flow for DeFi and Web 3.0 experiences directly from your favourite web browser.

- Securely send, receive, store, swap and stake tokens
- Non-custodial, open source and zero tracking privacy focus
- Web 3.0 support with ease in connecting with dapps directly from the browser
- Easy and intuitive staking to generate rewards for storing and securing the Polkadot network.

We will integrate Polkadot DOT and Kusama KSM in the HydroX Wallet. In our pipeline, the team is also considering to integrate other major chains in the ecosystem, such as Acala, Karura, Bifrost, Altair, Centrifuge, Nodle, Moonriver, Moonbeam, Darwinia and Crab.Network, etc.

### Project Details

We expect the teams to already have a solid idea about your project's expected final state. Therefore, we ask the teams to submit (where relevant):

- Mockups/designs of any UI components
- Data models / API specifications of the core functionality
- An overview of the technology stack to be used
- Documentation of core components, protocols, architecture, etc. to be deployed
- PoC/MVP or other relevant prior work or research on the topic
- What your project is _not_ or will _not_ provide or implement
  - This is a place for you to manage expectations and to clarify any limitations that might not be obvious

### Ecosystem Fit

Help us locate your project in the Polkadot/Substrate/Kusama landscape and what problems it tries to solve by answering each of these questions:

- Where and how does your project fit into the ecosystem?
- Who is your target audience (parachain/dapp/wallet/UI developers, designers, your own user base, some dapp's userbase, yourself)?
- What need(s) does your project meet?
- Are there any other projects similar to yours in the Substrate / Polkadot / Kusama ecosystem?
  - If so, how is your project different?
  - If not, are there similar projects in related ecosystems?

## Team :busts_in_silhouette:

### Team members

Samuel Austin - Project Lead (Team Leader)
Stefan Rust - Founder and CEO (Project Owner)
Robin Guyard - CTO
Nicholas Nups - Product Manager
Chelsea Miu - Partnerships and Business Development Lead

### Contact

- **Contact Name:** Chelsea Miu
- **Contact Email:** chelsea@hydrogenx.io
- **Website:** https://hydrogenx.io/

### Legal Structure

- **Registered Address:** Address of your registered legal entity, if available. Please keep it in a single line. (e.g. High Street 1, London LK1 234, UK)
- **Registered Legal Entity:** Hydro Labs Inc

### Team's experience

We are an experienced team with over 30 years’ experience in crypto and emerging tech. We have been developing, executing, delivering and growing businesses, ecosystems and communities globally. Each team member possesses comprehensive skills with specialties in software, tech, UX and marketing respectively. Our current project is [Trusted Node](https://trustednode.io). Our CEO is ex-CEO of [Bitcoin.com](https://www.bitcoin.com/); CTO worked on Blockchain Engineering at [Crypto.com](https://crypto.com/); Project Lead worked on [AppZaloot](https://appzaloot.com/), a blockchain-based social media app and Haven App, a decentralized cryptocurrency marketplace; Product Manager worked as Technical Project Manager at [HighVibe.Network](https://www.highvibe.network/) and Partnerhips & Business Development Lead worked as Brand Director at [MAD Gaze](https://www.madgaze.com), a leading consumer-focus augmented reality smart glasses and metaverse ecosystem company .

### Team Code Repos

- https://github.com/<your_organisation>
- https://github.com/<your_organisation>/<project_1>
- https://github.com/<your_organisation>/<project_2>

- https://github.com/Gniar/zencashjs
- https://github.com/Gniar/zenaddress
- https://github.com/polkadot-js/tools/issues/174
- https://github.com/polkadot-js/tools/issues/175

Please also provide the GitHub accounts of all team members. If they contain no activity, references to projects hosted elsewhere or live are also fine.

- https://github.com/Gniar/
- https://github.com/<team_member_2>

### Team LinkedIn Profiles (if available)
- https://www.linkedin.com/in/stefanrust/
- https://www.linkedin.com/in/robin-guyard/<Robin_Guyard>
- https://linkedin.com/in/sam-austin-75364663
- https://www.linkedin.com/in/nicolasnups/
- https://www.linkedin.com/in/miuchelsea/


## Development Status :open_book:

If you've already started implementing your project or it is part of a larger repository, please provide a link and a description of the code here. In any case, please provide some documentation on the research and other work you have conducted before applying. This could be:

- links to improvement proposals or [RFPs](https://github.com/w3f/Grants-Program/tree/master/rfp-proposal) (requests for proposal),
- academic publications relevant to the problem,
- links to your research diary, blog posts, articles, forum discussions or open GitHub issues,
- references to conversations you might have had related to this project with anyone from the Web3 Foundation,
- previous interface iterations, such as mock-ups and wireframes.

## Development Roadmap :nut_and_bolt:

This section should break the development roadmap down into milestones and deliverables. To assist you in defining it, we have created a document with examples for some grant categories [here](../docs/grant_guidelines_per_category.md). Since these will be part of the agreement, it helps to describe _the functionality we should expect in as much detail as possible_, plus how we can verify and test that functionality. Whenever milestones are delivered, we refer to this document to ensure that everything has been delivered as expected.

Below we provide an **example roadmap**. In the descriptions, it should be clear how your project is related to Substrate, Kusama or Polkadot. We _recommend_ that teams structure their roadmap as 1 milestone ≈ 1 month.

For each milestone,

- make sure to include a specification of your software. _Treat it as a contract_; the level of detail must be enough to later verify that the software meets the specification.
- include the amount of funding requested _per milestone_.
- include documentation (tutorials, API specifications, architecture diagrams, whatever is appropriate) in each milestone. This ensures that the code can be widely used by the community.
- provide a test suite, comprising unit and integration tests, along with a guide on how to set up and run them.
- commit to providing Dockerfiles for the delivery of your project.
- indicate milestone duration as well as number of full-time employees working on each milestone.
- **Deliverables 0a-0d are mandatory for all milestones**, and deliverable 0e at least for the last one. If you do not intend to deliver one of these, please state a reason in its specification (e.g. Milestone X is research oriented and as such there is no code to test).

### Overview

- **Total Estimated Duration:** 2 months
- **Full-Time Equivalent (FTE):**  5
- **Total Costs:** 50,000 USD

### Milestone 1 Example — Implement Polkadot, Kusama and Other Chain Modules

- **Estimated Duration:** 1 month
- **FTE:**  5
- **Costs:** 25,000 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0a. | License | Apache 2.0 / GPLv3 / MIT / Unlicense |
| 0b. | Documentation | We will provide both **inline documentation** of the code and a basic **tutorial** that explains how a user can (for example) spin up one of our Substrate nodes and send test transactions, which will show how the new functionality works. |
| 0c. | Testing Guide | Core functions will be fully covered by unit tests to ensure functionality and robustness. In the guide, we will describe how to run these tests. |
| 0d. | Docker | We will provide a Dockerfile(s) that can be used to test all the functionality delivered with this milestone. |
| 0e. | Article | We will publish an **article**/workshop that explains [...] (what was done/achieved as part of the grant). (Content, language and medium should reflect your target audience described above.)
| 1. | Substrate module: X | We will create a Substrate module that will... (Please list the functionality that will be implemented for the first milestone) |  
| 2. | Substrate module: Y | We will create a Substrate module that will... |  
| 3. | Substrate module: Z | We will create a Substrate module that will... |  
| 4. | Substrate chain | Modules X, Y & Z of our custom chain will interact in such a way... (Please describe the deliverable here as detailed as possible) |  


### Milestone 2 Example — Additional features

- **Estimated Duration:** 1 month
- **FTE:**  5
- **Costs:** 25,000 USD

...


## Future Plans

Please include here

- how you intend to use, enhance, promote and support your project in the short term, and
- the team's long-term plans and intentions in relation to it.


## Additional Information :heavy_plus_sign:

**How did you hear about the Grants Program?** Web3 Foundation Website

The project has already kicked off after scope clarification, design verifications and user story refinement. Development has begun.

- Wheter there are any other teams who have already contributed (financially) to the project.
