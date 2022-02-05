# Awesome Secret List :shushing_face: 𝕊

This is a list of great [Secret Network](https://scrt.network) related projects, tools, games, and more!

Feel free to suggest changes as discussions, issues, or PRs :sparkles:

* [General Resources](#general-resources)
* [Products](#products)
* [Games](#games)
* [Explorers](#explorers)
    * [Mainnet](#mainnet)
    * [Testnet](#testnet)
    * [Staking Calculators](#staking-calculators)
* [Wallets](#wallets)
* [User Guides](#user-guides)
* [Developer Guides](#developer-guides)
* [Developer Tools](#developer-tools)
* [Reference Contracts](#reference-contracts)

## General Resources
Official Secret Network resources

* [Main website!](https://scrt.network/) - Official Secret Network website
* [Blog](https://scrt.network/blog/) - Official Secret Network blog
* [Wiki](https://docs.scrt.network/) - Official Secret Network wiki
* Graypaper by Carter Woetzel - [Web](https://scrt.network/graypaper) · [PDF](https://www.securesecrets.org/papers)
* [Specifications](https://github.com/SecretFoundation/SNIPs/) - SNIPs - Secret Network Improvement Proposals

Community activity

* Community channels: [Forum](https://forum.scrt.network/) · [Discord](https://chat.scrt.network) · [Telegram](https://t.me/scrtCommunity) ·
    [Reddit](https://www.reddit.com/r/SecretNetwork/) · [Twitter](https://twitter.com/SecretNetwork)
* [Community Calendar](https://www.secretcalendar.org/) - A calendar of upcoming events, curated by several community members
* [Secret Agent Headquarters](https://scrt.network/agents) - Home for community member collaboration
* [Grant Applications](https://github.com/SecretFoundation/Grants/issues) -
    [announcement](https://scrt.network/blog/announcing-secret-network-grant-program) ·
    [ideas](https://scrt.network/grant-application-ideas) ·
    [process](https://scrt.network/grant-application-process)
* [SNACs](https://forum.scrt.network/t/open-discussion-snacs-secret-network-action-campaigns/3150) -
    Secret Network Action Campaigns
* [Secret Fellows](https://scrt.network/blog/secret-fellows-developer-program) - Developer mentorship program

## Products
Large products that launched (or will launch very soon) on the Secret Network

### bridges
* [Secret Bridges](https://bridge.scrt.network/) - Turn assets from other chains into SNIP-20 privacy tokens
    * Support for ETH and ERC-20 tokens
        * Integrated to [keyTango](https://app.keytango.io/invest) easy DeFi investment interface
        * [Alternate UI](https://linkswap.app/#/scrt) by [YF Link][yflink]
    * Support for BNB and BEP-20 tokens
    * Also supported in [Citadel One][citadel] wallet
* [Secret Monero Bridge](https://ipfs.io/ipfs/QmNRrLDhKGZCSXAZcPU1cBTaLouhWnTi5kfWUzJB4nJbzA) - Turn your XMR into the SNIP-20 sXMR
* [IBC bridges](https://wrap.scrt.network/) - Transfer tokens across IBC networks and wrap them in SNIP-20 tokens
    * Alternate UI for [IBC bridging](https://app.sienna.network/wrap) and [SNIP-20 wrapping](https://app.sienna.network/wrap/ibc) of IBC tokens, by [Sienna]
* :soon: [Shinobi Protocol](https://sbtc.ninja) - Trustless bridge to Bitcoin. Turn your BTC into the SNIP-20 sBTC

### DeFi
* [secretSCRT Converter](https://wallet.keplr.app/#/secret/secret-secret) - Convert between SCRT and sSCRT, by [Chainapsis][chainapsis]
    * Also available in [Citadel One][citadel] wallet
* [Secret Swap](https://www.secretswap.net/) - Front running resistant AMM
* [Sienna Network][sienna] - Front running resistant AMM, and more products in the future
* [Button Swap](https://www.btn.group/secret_network/button_swap) - AMM/DEX aggregator by [btn.group]
* :soon: [Shade Protocol](https://shadeprotocol.io/) - an array of connected privacy-preserving DeFi applications
    * **Shade** - Governance token
    * **Silk** - Algorithmic stablecoin with transactional privacy by default
    * **Synthetics** - Algorithmic synthetic assets with transactional privacy by default
    * Many more will be revealed :shushing_face:
* :soon: [StakeEasy](https://stakeeasy.finance/) - Privacy preserving liquid staking solution for Secret Network.
* [Duplex Finance](https://duplex.finance/) - Two-fold cross-chain strategy for gaining yield on stablecoins
* [Secret Auctions](https://auctions.scrt.network/) - Sealed-bid auctions and OTC market

### NFT
[Stashh](https://stashh.io/) - Marketplace for Secret NFTs
* [Anons](https://www.anons.army/) - First NFT project to launch on the network. Only 580 anons.
    [Twitter](https://twitter.com/AnonsNFT) · [Contract](https://secretnodes.com/secret/chains/secret-3/contracts/secret1xx4fp7qgkyxdk9elrzd8v5p7gj28lvxprwl9lw)
* [Tarantino NFTs](https://tarantinonfts.com/) - Seven uncut scenes from the original Pulp Fiction manuscript
* [... More projects listed here](https://secretnft.com/scrt-nft-projects)

### Other
* [Fardels](https://fardels.network/) (beta) - An decentralized social network for selling items of low value
* [Altermail](https://altermail.co/) - A decentralized messaging service dApp
* [Secret Garden](https://scrtgarden.com/) - Secret Token and Secret NFT generator, manager, and explorer by [Secret Garden](https://github.com/ScrtGarden)
* :soon: [JACKAL](https://jackaldao.com/) - A completely decentralized hot storage on-chain that uses the Amazon S3 Standard. 

## Games
Cool games built on the network

* :soon: _**Orbem Wars**_ by [Domerium Labs](https://twitter.com/DomeriumLabs) ([Blog](https://medium.com/@domeriumlabs)), is a P2E tower defense game with four game modes, including single-player, multi-player, and PvP. Its combat and NFT-based economy are balanced to continuously challenge players to rethink their setups.
* [Secret Dreamscape](https://secretdreamscape.com/) by [Secret Dreamscape](https://twitter.com/SCRTDreamscape) ([Blog](https://blog.secretdreamscape.com/posts/introducing-secret-dreamscape/)), is a social multiplayer game that's like a mashup of poker and scrabble. The cards are rich with fantastical images that take the player somewhere between a dream and reality. Players can bring their personal deck of NFT cards and craft new dreamscapes into the cards as they play. Currently on testnet 
* [prisnr.games](https://prisnr.games/) - Head-to-head strategy game on testnet invoking the prisoner's dilemma. Implements private entropy pool for random numbers and secretNFTs as rewards and playable in-game power-ups. ([Contract codebase](https://github.com/prisnr-games/secret-dapp/tree/master/contracts), [Front-end webapp code](https://github.com/prisnr-games/webapp))
* [Secret Heroes](https://secrethero.es/) - Deck building, auto-battler game based on collectible secretNFTs, built in Unity
* [Secret Holdem](https://holdem.enigma.co/) - Texas Holdem game on testnet ([Codebase](https://github.com/enigmampc/SecretHoldEm/))
* [Rock Paper Scissors](https://testrps.lindlof.io/) - Rock paper scissors game without commit-reveal on testnet ([Codebase](https://github.com/lindlof/secret_rock_paper_scissors))

## Explorers
Block Explorers and visualization tools

### Mainnet
* [Secretnodes](https://secretnodes.com) - Highly featured explorer, originally funded by the network, run by validator [Secretnodes][secretnodes]
* [Mintscan](https://www.mintscan.io/secret) - Popular and highly featured explorer for many chains in the Cosmos ecosystem
* [Secret Contracts](http://secret-contracts.com/) - Contract code verifier and explorer by [3Dgiro][3dgiro]
* [Secret Analytics](https://secretanalytics.xyz/) - Analytics data collected about the Network, Bridges, and SecretSwap
* [SmartStake Secret Analytics](https://secret.smartstake.io/) - Validator stats by [SmartStake]
* [Xiphiar](https://scrthost.xiphiar.com/) - Tools by Xiphiar for better analysis of your SecretSwap LP tokens
* [Address alias](https://btn.group/secret_network/address_alias) - Create and search wallet aliases, by [btn.group]
* ~~[Cashmaney Explorer](https://explorer.cashmaney.com)~~ (retired) - One of the first explorers, run by core-dev Cashmaney

### Testnet
`pulsar-2`, [Docs](https://github.com/scrtlabs/testnet/blob/master/pulsar-2/details.md) - Maintained by the [Stashh](https://stashh.io/) team
* [Faucet](https://faucet.secrettestnet.io/) - Run by validator [Chain of Secrets][chainofsecrets]
* [Secretnodes](https://secretnodes.com/secret/chains/pulsar-2) - Highly featured explorer, originally funded by the network, run by validator [Secretnodes][secretnodes]

`holodeck-2`, [Docs](https://github.com/scrtlabs/testnet/blob/master/holodeck-2/details.md) - Maintained by validator [Chain of Secrets][chainofsecrets]
* ~~[Faucet](https://faucet.secrettestnet.io/)~~ - Run by validator [Chain of Secrets][chainofsecrets]
* [Secretnodes](https://secretnodes.com/secret/chains/holodeck-2) - Highly featured explorer, originally funded by the network, run by validator [Secretnodes][secretnodes]
* ~~[SecretTestnet](https://explorer.secrettestnet.io/)~~ (retired) - Explorer run by validator [Chain of Secrets][chainofsecrets]

### Bots
* [Gas Attendant](https://t.me/SCRT_GasAttendant_bot) - Time your transactions with notifications for blocks with low or high gas fees, by secretSauce :honey_pot:
* [Node Hunter](https://t.me/SCRT_Node_Hunter_bot) - Get notified if a validator has been offline for a long time, by secretSauce :honey_pot:

### Staking Calculators
* [For stakers](https://www.securesecrets.org/stakingcalculator) · 
    [For validators](https://www.securesecrets.org/validatorcalculator) -
    By validator [Secure Secrets][securesecrets]
* [For stakers](https://stakeordie.com/rewards-calculator) - By Validator [Stake or Die][stakeordie]
* [For stakers](https://www.stakingrewards.com/earn/secret-network) - By [Staking Rewards](https://www.stakingrewards.com)
* [For stakers](https://secret.smartstake.io/calc) - By [SmartStake]

## Wallets
Great and popular wallets for managing your Secret Address

* [Keplr](https://keplr.app) by [Chainapsis][chainapsis]
    * Highly featured wallet for the entire Cosmos ecosystem
    * First wallet with full support of SNIP-20 Secret Tokens
    * **Support for usage from any Secret dApp**
    * Convert between SCRT and sSCRT ([in web app](https://wallet.keplr.app/#/secret/secret-secret))
    * Web app + Browser extension + Mobile wallet
* [Citadel One][citadel]
    * Great UI and assortment of supported networks
    * Second wallet with full support of SNIP-20 Secret Tokens
    * Built-in support for sending assets across the Ethereum Bridge
    * Convert between SCRT and sSCRT
    * Validator on the network
    * Web app + Mobile wallet
* [Secret Tipbot](https://twitter.com/secret_tipbot) by validator [SG-1][sg-1] ([Guide](https://medium.com/@Cosmostipbot/the-secret-tipbot-is-now-live-d2bd7ef1be94))
    * Funded by the community ([Proposal](https://secretnodes.com/secret/chains/secret-2/governance/proposals/26))
    * Send SCRT to other Twitter users with a tweet
    * Send SCRT to other Telegram users with a command
* [Sputnik Exchange](https://sputnik.exchange/) ([Guide](https://www.youtube.com/watch?v=NwiI6xXkMcw))
    * Send SCRT to other Twitter users with a tweet
    * Send SCRT to other Telegram users with a command
    * Buy and sell SCRT from/to other users of Sputnik
* [Ledger](https://docs.scrt.network/guides/ledger-nano.html) - Guide to using Ledger hardware wallet with Secret Network 

## User Guides
Guides about using the Secret Network

### Text Tutorials

* [Secret Network Medium](https://medium.com/@secretnetwork) - Guides for products in the ecosystem,
* [Secure Secrets Tutorials](https://securesecrets-org.medium.com/secure-secrets-tutorials-meta-thread-df51b84fa35) -
    Guides on using products in the ecosystem by validator [Secure Secrets][securesecrets]
* [Altcoin Buzz Tutorials](collections/altcoinbuzz-guides.md) - Guides by [Altcoin Buzz][acb]
* More tutorials available on the Secret Network [Blog](https://scrt.network/blog/)

### Video Tutorials

* [Official Secret Network Youtube](https://www.youtube.com/c/SecretNetworkOfficial) - Run by the Secret Foundation
* [Whisper Node Youtube](https://www.youtube.com/channel/UChAbgpsMHT3ooZfWmjjUtKg/videos) - By validator [Whisper Node][whispernode]
* [Secure Secrets Youtube](https://www.youtube.com/c/SecureSecrets/videos) - By validator [Secure Secrets][securesecrets]
* [Travis Bonfigli Youtube](https://www.youtube.com/playlist?list=PL6Tc4k6dl9kK4gmFDdMXVwTiXuS-COgV8) - Has a series on Secret Network
* [Secret Code Podcast YouTube - Tutorial Playlist](https://www.youtube.com/watch?v=C0zRTaV8XgI&list=PLxrw7YCKLEXvPNUJ1SFoHQUUQa4_Uwwdg) - By validator [Secret Code Podcast Node](http://secretcodepodcast.com)

### Podcasts

* [Sharing Secrets](https://www.youtube.com/watch?v=-l-c25mhE1M&list=PLL1JDiTNCUAVq9YeGbxDtqBgaqUZajGIH) - Hosted by [Tor Bair](https://twitter.com/TorBair/)
* [Secret Code](https://www.secretcodepodcast.com/) - Hosted by [Eric Waisanen](https://twitter.com/EricWaisanen)
    and [Paul Menexas](https://twitter.com/SecretKnight)
    ([Twitter](https://twitter.com/secretcodepod))

## Developer Guides
Guides about building on the Secret Network

* [Official Guides](https://docs.scrt.network/dev/developers.html) - Official Guides written by the community
    * [Quickstart](https://docs.scrt.network/dev/quickstart.html) - Set up your environment and start writing contracts as fast as possible
    * [Tutorials](https://docs.scrt.network/dev/tutorials.html) - More specific tutorials for different use cases
* [Figment Learn](https://learn.figment.io/protocols/secret) - Guides and Tutorials by [Figment][figment]
* [Creating my first secret contract](https://darwinzero.medium.com/creating-my-first-secret-contract-on-secret-network-scrt-db0d04597051) -
    Tutorial by DarwinZero
* [Developing your first secret contract](https://github.com/darwinzer0/secret-contract-tutorials/tree/main/tutorial1) -
    Tutorial by DarwinZero
* [How to build a Keplr Staking Web App](https://securesecrets-org.medium.com/secret-network-developer-tutorial-how-to-build-a-keplr-staking-app-49dfeb25abe4) -
    Tutorial by validator [Secure Secrets][securesecrets]
* [Band oracle integration docs](https://hackmd.io/@tansawit/secret-network-developer-doc) - by [Band Protocol](https://bandprotocol.com/) ([Announcement](https://scrt.network/blog/band-protocol-live-on-mainnet))

## Developer Tools
Tools for interacting with the secret network and for writing Secret Contracts

* [Local Node](https://hub.docker.com/r/enigmampc/secret-network-sw-dev) - Start a docker container with a standalone network
* [Secret DataHub](https://figment.io/datahub/secret-network/) by [Figment][figment] - Quickly set up a Secret Node on mainnet or testnet for your application
* [Secret API](https://secretapi.io/) - Web API for using Secret Network by [Chain of Secrets][chainofsecrets]
* [SecretJS](https://www.npmjs.com/package/secretjs) - JavaScript library for interacting with the network
    ([examples](https://github.com/enigmampc/SecretJS-Templates))
* [Griptape.js](https://griptapejs.com/) - By Validator [Stake or Die][stakeordie], a front-end web framework for developing DApps on the network
* [Polar](https://www.npmjs.com/package/secret-polar) - Polar is a framework for building secret contracts. It features facilitates for [project templates](https://github.com/arufa-research/polar-templates), compilation, deployment, javascript interaction (based on schemas), and testing
    ([Docs](https://docs.arufaresearch.com/),
    [Codebase](https://github.com/arufa-research/polar))
* [Secret Toolkit](https://github.com/enigmampc/secret-toolkit) - Extra tools for use in Secret Contracts
* [Smart Contract Interface](https://www.btn.group/secret_network/smart_contract_interface) - Browser interface for smart contracts by [btn.group]

## Reference Contracts
Examples of reference Secret Contract implementations

* [Secret Template](https://github.com/enigmampc/secret-template) - Quickstart template to start developing Secret Contracts
* [SNIP-20](https://github.com/enigmampc/snip20-reference-impl) - Reference SNIP-20 contract implementation (Secret Tokens)
* [SNIP-721](https://github.com/baedrik/snip721-reference-impl) - Reference SNIP-721 contract implementation (Secret NFTs)
* [Randomized NFT Minting](https://github.com/luminaryphi/secret-random-minting-snip721-impl) - Template for launching NFT projects that need randomized minting
* [Secret Dice](https://github.com/enigmampc/SecretDice) - Example of on-chain randomness based on encrypted inputs and state + video tutorial

<!-- contributor links -->
[acb]: <https://altcoinbuzz.io/>
[btn.group]: <https://www.btn.group>
[chainapsis]: <https://chainapsis.com/>
[chainofsecrets]: <https://chainofsecrets.org/>
[citadel]: <https://citadel.one>
[figment]: <https://figment.io/>
[secretnodes]: <https://secretnodes.org>
[securesecrets]: <https://www.securesecrets.org>
[sg-1]: <https://sg-1.online/>
[sienna]: <https://sienna.network/>
[SmartStake]: <https://smartstake.io/>
[stakeordie]: <https://stakeordie.com/>
[whispernode]: <https://www.whispernode.com/>
[yflink]: <https://yflink.io/>
[3dgiro]: <https://3dgiro.com/>
