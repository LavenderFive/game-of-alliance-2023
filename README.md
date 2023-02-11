<p align="center">
  <img src="https://user-images.githubusercontent.com/9121234/190864636-b5047a5b-8f44-42ed-a9de-62095bebd2a3.jpg" />
</p>

# Game of Alliance 2023  
## Resources
[Bounty Submission](https://docs.google.com/forms/d/e/1FAIpQLScdnf07cVebzXRURTeg8bnBgNa3PEZEwq9Oke4Edd-TaKDAow/viewform)  
[Docs](https://alliance.terra.money/)  
[Join Testnet](https://github.com/terra-money/alliance/tree/feat/wasm-testnets#join-the-game-of-alliance-testnet)  
[Staking & Faucet](https://game-of-alliance.terra.money/)  
  
[Address Books](https://github.com/LavenderFive/game-of-alliance-2023/tree/master/addrbook)  
[Genesis Files](https://github.com/LavenderFive/game-of-alliance-2023/tree/master/genesis)  
[Tenderduty Config Template](https://github.com/LavenderFive/game-of-alliance-2023/tree/master/tenderduty)  
  
## Atreides  
RPC: https://goa-atreides-rpc.lavenderfive.com/  
gRPC: `https://goa-atreides-grpc.lavenderfive.com`  
API: `https://api-atreides.goa.lavenderfive.com` 
  
Seed: `d634d42f4f84caa0db7c718353090fd7973e702e@goa-seeds.lavenderfive.com:13656`  
Validator: `atreidesvaloper14qekdkj2nmmwea4ufg9n002a3pud23y8rz2qmg`
  
## Corrino  
RPC: https://goa-corrino-rpc.lavenderfive.com/   
gRPC: `https://goa-corrino-grpc.lavenderfive.com/`  
API: `https://goa-corrino-api.lavenderfive.com/`  
  
Seed: `2a78b8849872d641d61d97b95f7349540e9d8df0@goa-seeds.lavenderfive.com:12656`  
Validator:  `corrinovaloper14qekdkj2nmmwea4ufg9n002a3pud23y8gljwt3`
  
## Harkonnen  
RPC: https://goa-harkonnen-rpc.lavenderfive.com/  
gRPC: `https://goa-harkonnen-grpc.lavenderfive.com/`  
API: `https://goa-harkonnen-api.lavenderfive.com/`  
  
Seed: `1772a7a48530cc8adc447fdb7b720c064411667b@goa-seeds.lavenderfive.com:11656`  
Validator:  `harkonnenvaloper14qekdkj2nmmwea4ufg9n002a3pud23y8yz54hu`
  
## Ordos  
RPC: https://goa-ordos-rpc.lavenderfive.com/  
gRPC: `https://goa-ordos-grpc.lavenderfive.com`   
API: `https://goa-ordos-api.lavenderfive.com/ `  
  
Seed: `71f96fe3eec96b9501043613a32a5a306a8f656b@goa-seeds.lavenderfive.com:10656`   
Validator:  `ordosvaloper14qekdkj2nmmwea4ufg9n002a3pud23y8k3pp9c`
  
## Who Are We
[Lavender.Fives Nodes](https://www.lavenderfive.com/) is one of the most trusted Proof of Stake validators. 
Our team is able to maintain industry-leading uptime through a variety of resources including dedicated servers around the world, 
multiple 24/7 alerting systems in place, and always-ready backups. We are proud to say we serve as validators on more than 30 mainnets, 
and are trusted by over **30,000 delegators**. 

We differentiate ourselves through our community engagement and contributions to the projects we serve. 
This is achieved by authoring documentation for fellow validators, writing and promoting new governance proposals, 
and helping squash code bugs before they become an issue.

## Our Infrastructure

We take a pragmatic approach to running validators. At the most basic level we utilize bare metal servers with a minimum of 2 full nodes per network. 
Each server is with a different providers, Hetzner, OVHCloud, or MEVspace, spread across multiple geographic locations.
In addition, we utilize [Horcrux](https://github.com/strangelove-ventures/horcrux) as our remote signing solution, with 3 signers. What this means in practice is *ALL* nodes have to go down, or 2 signers, before we miss a single block.

In addition to this, we utilize the following as our monitoring solutions:
- [Zabbix](https://www.zabbix.com/)
- [Prometheus](https://prometheus.io/)
- [Tenderduty](https://github.com/blockpane/tenderduty)

## Our Contributions

We also contribute greatly to each ecosystem we're in. 

As a few off the cuff examples:
- **Open source tooling for validators/node runners**:
  - Core maintainer of the [Cosmos Chain Registry](https://github.com/cosmos/chain-registry) 
  - Ansible playbooks for [Horcrux](https://github.com/LavenderFive/horcrux-ansible)
  - Ansible playbooks for [running nodes](https://github.com/LavenderFive/cosmos-validators-ansible)
  - Ansible playbooks for [secure server setup](https://github.com/LavenderFive/secure-server-setup-ansible)
  - [Tendermint slashing refund script](https://github.com/LavenderFive/slash_refunds_tendermint)
- We provide **public RPC, API, and gRPC endpoints** for every network we have a presence on
- We maintain **state sync snapshots** for every network
- We provide a public **seed node** for each network we are on
- **Relaying**: we are one of the most prolific relayers in the ecosystem, and have helped many relayers get their start (see the docs below)
- We wrote the Gentx documentation for [Kujira](https://github.com/Team-Kujira/networks/pull/5), Defund, Odin, Chihuahua, Dig, and more
- We've either written or edited every document for [Secret Network](https://docs.scrt.network/)
- We write documentation to help other node runners:
  - [Relaying](https://docs.scrt.network/relayers/setting-up-hermes.html)
  - [Setting up TMKMS](https://gist.github.com/dylanschultzie/c7c4eed531df0f004a50c5395e1604b3)
  - [Horcrux](https://gist.github.com/dylanschultzie/0a0b10cf695749f9697197759e7b12ec)
  - [Raising the Security Floor of the Cosmos](https://medium.com/@lavenderfive/raising-the-security-floor-of-the-cosmos-2467f5e71966)
- We commonly create proposals for networks:
  - [Osmosis](https://commonwealth.im/osmosis/proposal/discussion/2487-proposal-discussion-signaling-proposal-for-scrt-incentivized-pools)
  - [Secret](https://secretnodes.com/secret/chains/secret-4/governance/proposals/93)

## A Showing of Networks
A small selection of the networks we support include:
- Secret Network
- Cosmos Hub 
- Osmosis
- Evmos
- Juno
- NEAR
- [and many more!](https://www.lavenderfive.com/)
