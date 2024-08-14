# Vyper Polygon Grant

## Section 2: Project & Team Overview

### Logo

![2024-06-11_23-25](https://github.com/user-attachments/assets/86b9c01b-a6ca-43d9-9cf1-3e1b9aee1809)


### Company Name

Vyper Labs

### Project's Polygon PoS wallet address (EOA/Multisig)*

`0xAbfA48BCc0F96Fc70be7a4156b0a74Ea350167fD`

### What best describes your project?*

Indie Dev Team

### Team size*

3-5 people

### Core-team Country*

_List all countries_

United States, Greece

### Have you raised any VC/Accelerator/other grant funding to-date?*

No

### If yes, Name the VC/Chain ecosystems/Accelerators you've raised money from?*

N/A

### If yes to above, what is your funding stage*

B/A

### What category best describes the project?*

Dev Tooling

### What secondary category would you choose to describe your project?*

Infra

### How long have you been working on the project for?*

More than 2 years

### What phase is your project?*

We have a working, user facing product deployed

### Is your project live?*

Yes

### Project Pitch Deck *

Docsend link only

### Project Discord*

https://discord.gg/WNKFpCtr

### Project Whitepaper

### Project dApp Link

https://vyperlang.org/

### Project TVL

Vyper secures over $2 billion of TVL (https://defillama.com/languages)

### Contract Address


### Contract Audits

https://github.com/vyperlang/audits

### Total Transactions

### Total Unique Addresses that Interacted with the Protocol

Millions of unique addresses have interacted with the 20k+ Vyper contracts deployed across a dozen chains.

### Project supported chain ecosystems

We support all EVM chains, Vyper contracts are deployed and active on Polygon, Ethereum, Optimism, Base, Arbitrum, Fantom, Fraxtal, Celo, Avalanche, Moonbeam, zkSync, Harmony, Gnosis Chain

### What kind of grant do you seek? *

Large scale Ecosystem grant

## Section 3: Project/Idea exploration

### Please clearly state what the project is about, what problems it is trying to solve, why the project thinks those problems are important and why you or your team are the one to solve those problems. *

We are developing a readable, efficient and secure programming language for smart contracts.

Problems We're Solving:

1. Security Vulnerabilities: Other smart contract languages often introduce security risks through features like inline assembly and class inheritance. Vyper eliminates these pitfalls, and instead focuses on making contracts simple to read and therefore easier and cheaper to audit. The team is also working on implementing better out-of-the-box testing and fuzzing features as well as state of the art compiler verification methods, ensuring comprehensive and robuts security across all aspects of development. 

2. Contract Bloat: Other compilers often produce contracts with bloated bytecode and gas costs that are higher than they should be. Thanks to a highly optimized backend, Vyper already consistently produces binaries 50% smaller than Solidity, with significantly lower gas consumption (https://blog.chain.link/solidity-vs-vyper/, https://github.com/z80dev/gascomps, https://github.com/benber86/vyper_bytecode) and we will continue to improve this headstart.

3. Language Centralization: Most EVM smart contracts are written in Solidity which is a strong centralization vector and security risk. Vyper is currently the only real alternative 

4. Developer Onboarding: Vyper's pythonic syntax makes it easy to onboard new developers to web3, as Python is now the most popular programming language (Stack Overflow survey 2024, https://survey.stackoverflow.co/2024/). A recent Twitter poll with 164 participants showed that a majority of developers would pick Vyper and Ape over Solidity and Foundry to start a new project (https://x.com/0xKoga/status/1805524364948893756).

### Are you already deployed on Polygon and if so, what date did you deploy?*

Vyper contracts have been deployed to Polygon since at least 2021.

### How does your project implement the Polygon blockchain and which parts will be on-chain?*

Vyper supports Polygon and all EVM chains. Vyper contracts are used by protocols such as Curve and Yearn on Polygon.

### Describe your team composition, relevant competencies and previous achievements*

The Vyper team is composed of highly experienced web3 engineers with expertise in compilers and security, with an extensive understanding of the EVM, smart contract development, and the associated security considerations. They have collaborated extensively with auditors and security researchers, contributed to the growth of the Ethereum ecosystems via EIPs, and their expertise is widely recognized within the EVM developers and security communities. The project also has over 20 regular contributors. The team currently consists of:

- Charles (https://github.com/charles-cooper, https://x.com/big_tech_sux). Charles is the lead developer of Vyper and Titanoboa (https://github.com/vyperlang/titanoboa). Charles also contributes to multiple Ethereum tooling projects (py-evm, pyrevm, eth-abi) and is the author of several EIPs.
- Harry (https://github.com/harkal, https://x.com/harkal). Harry has been working on Vyper's intermediate representation (Venom) since 2023. Harry has over 10 years of experience in embedded programming and computer graphics.
- cyberthirst (https://github.com/cyberthirst). Cyberthirst is a Vyper contributor who has worked on compiler security since 2023 and has an academic background in compiler verification research.
- Adam (https://github.com/hodanplodky). Adam is a web3 engineer working on Vyper's intermediate representation.

### Indicate your current traction (MAU, DAU, retention, TVL or other relevant metrics) if your product is already live on Polygon or on a different chain*

Vyper is used by Curve ($18m TVL on Polygon: https://defillama.com/protocol/curve-finance#tvl-charts) and Yearn ($11m TVL on Polygon: https://defillama.com/protocol/yearn-finance#tvl-charts)

### Who are your competitors? Are there any similar existing solutions on Polygon? If yes, mention similar solutions and elaborate on your product's advantages.*

Vyper's main competitors are other smart contract programming language such as Solidity, Fe and Yul. Vyper differs by its focus on readability, security and simplicity. Vyper is designed to make contract maximally human readable. This translates in a direct reduction (-20% according to auditors) of the time and costs of auditing Vyper contracts. Simplicity translates to more optimized contracts, which have, on average 50% smaller bytecode and less gas costs. Vyper's simple, pythonic syntax and the absence of footguns (operator and function overloading, class inheritance, etc.) makes it easy to onboard new developers already familiar with Python.

### Please describe your target user, and user acquisition strategy

We are targeting smart contract developers and new developers interested in transitioning to web3. Our user acquisition strategy currently consists of:

- Outreach: Attending web3 conferences and organizing workshops to showcase Vyper's features. Supporting Vyper tutorials on YouTube and other social media platforms.
- Tooling: We have worked tirelessly on developing new tooling to offer a superior developer experience compared to other smart contract programming languages.

### What is your vision on further funding steps once your grant scope is complete?*

Vyper currently relies solely on grants to fund its development. We will continue to apply for grant after completion of the current scope to continue to fund the development of new features.

### Overview of the technology stack to be used*

Vyper is written entirely in Python

### Is/Will your project be open sourced?*

Vyper is open source and released under the permissive Apache license.

### How will the project contribute to the Polygon ecosystem?*

- Enhanced Security: Vyper's design choices and stringent audit processes increase the security of smart contracts on Polygon, reducing the risk of exploits and vulnerabilities.
- Language Diversity: Vyper contributes to language diversity in the Polygon ecosystem. This diversity is crucial as it reduces the risk of systemic failures that could arise from vulnerabilities in a single programming language. It also provides developers with more choices, allowing them to select the language that best fits their project needs and expertise.
- Optimized Contracts: Vyper's compiler optimizations allow developers to create more complex contracts without hitting EVM size limits, improving overall contract efficiency.
- Developer Ecosystem: By offering Python-like syntax, Vyper lowers the barrier to entry for smart contract development and can appeal to web2 developers already familiar with Python, fostering a larger developer community on Polygon.


### What is your research about, how does it expand Polygon, and how does it benefit the Ethereum ecosystem?

N/A

## Section 4: Grant details

### What is the size of your grant request? (Enter specific numeric POL Amount)*

50,000 MATIC

### How do you plan on allocating funds?*

Our primary objective is to fund research on and implementations of state of the art compiler verification methods by a security researcher.

The goals are to:

Test the correctness of the Vyper compiler, searching for any potential bytecode and source code semantic divergences.
Mitigate systemic risk in the core infrastructure. This is particularly important as a compiler issue could potentially endanger the entire ecosystem.
Automate and expand our testing processes to reduce costs associated with audits and decrease development time.


### Milestones

Implementation of a definitional interpreter (3 months) - 20k MATIC
Vyper program generator (2 months) - 20k MATIC
Differential fuzzing against the interpreter (1 month) - 10k MATIC

Metrics:

Number of bugs and vulnerabilities detected and fixed through the new verification methods
Reduction in occurence of high severity bugs (based on audits and bug bounty results before and after completion of the project)
Increase in test coverage percentage for the Vyper compiler codebase
