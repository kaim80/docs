
# [⏎](../README.md) Iteration 2

The `Iteration 2` is a third evolutionary step of the KIRA Network. The main goal of this iteration is to deploy a usable Mainnet, where independent users could control and manage the network. The subject of the testnet will be economic sustainability and seamless upgrade experience. 

## Roadmap

The Mainnet iteration consist of 3 milestones that must be completed with defined below capabilities. This iteration scope is also divided into **OPTIONAL** :new_moon: and **ESSENTIAL** :full_moon: tasks. Each task also contains a status, which is **PENDING** :x:, **ACTIVE** :pick: or **COMPLETED** :white_check_mark:. Each feature :zap: MUST have assigned [:bookmark:KIP] (Kira Improvement Proposal) tags to each of it's tasks and dedicated documentation page.

To learn more about branches and development process, see [versioning](../versioning.md) documentation.

_NOTE: All OPTIONAL :new_moon: features CAN become the scope of the future iterations and are NOT a priority for delivery._

1. :link: **Blockchain Application**
   * :zap: Consensus
     * :x: :full_moon: [[:bookmark:KIP_52]](kip_52.md) Fee Rewards Distribution
   * :zap: Governance
     * :x: :full_moon: [[:bookmark:KIP_53]](kip_53.md) Spending Pools
     * :x: :full_moon: [:bookmark:KIP_X] Upgrade Proposal & Revert
   * :zap: Security
     * :x: :full_moon: [:bookmark:KIP_X] Global Transfers Un/Freeze
2. :globe_with_meridians: **[REST Server / JSON RPC](../rpc/README.md)**
   * :zap: Queries 
      * :x: :full_moon: [:bookmark:KIP_X] TBD
   * :zap: Availability
      * :x: :new_moon: [:bookmark:KIP_X] TBD
3. :computer: **User Interface / Deployment**  
   * :zap: Network Management
      * :x: :full_moon: [:bookmark:KIP_X] TBD
   * :zap: Governance
      * :x: :full_moon: [:bookmark:KIP_54] Spending Pool Management
   * :zap: Asset Management
      * :x: :new_moon: [:bookmark:KIP_X] TBD
   * :zap: Node Management
      * :x: :full_moon: [:bookmark:KIP_X] On-chain Upgrade & Revert 

### Dependency Map

_This map defines order in which tasks must be executed to fulfill goals of the `Iteration 2`_

**KIP X** ⬅ **KIP Y** 

## Objective

The main goal of `Iteration 2` is to deploy a mainnet network that can be easily maintained.

## Foreword

Various technical definitions relevant to `Iteration 2` can be found in [glossary](../glossary.md). In case any part of the documentation is not clear, or difficult to understand, please create a relevant github issue.

We should always aim to maintain CLI up to date with latest changes and ensure that default output is JSON formatted as well as all exceptions result in appropriate exit code's != 0.

