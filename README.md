# KIPs

KIPs stand for KIRA Improvements Proposals.

- [KIRA's Core KIPS](#kiras-core-kips)
  - [KIP Group 1 - Validator Staking](#kip-group-1---validator-staking)
  - [KIP Group 2 - Governance](#kip-group-2---governance)
- [KIP List](#kip-list)
- [How to Submit a KIP?](#how-to-submit-a-kip-)
  - [Create your KIP](#create-your-kip-markdown-file-following-these-requirements)
  - [Submit your KIP](#submit-your-kip-by-raising-a-pr-to-master)
- [Contributors](#contributors)

## KIRA's Core KIPS

The following KIPS are foundational proposals that have been authored and implemented by KIRA's core team. These proposals are foundational to the network's current structure and functionality. These KIPS have been grouped together to provide a comprehensive overview of the mechanisms and innovations that form the backbone of KIRA.

### KIP Group 1 - Validator Staking

KIPs 71-75 propose the creation of economic incentives for KIRA consensus nodes. As these consensus nodes are required to stake assets with economic value as slashable collateral, it is also necessary to reward them for performing their duties. KIP 71 proposes the spending pool structure used by KIPs 72 and 73 to distribute rewards to consensus nodes. KIPs 74 and 75 outline the incentive structures that govern staking rewards and slashing punishments for consensus nodes. 

- [KIP 71 - Spending Pools](kips/71.md): KIP 71 proposes a spending pool mechanism for distribution of different tokens to eligible accounts. Its main use cases are tied to the distribution of staking rewards, UBI (Universal Basic Income) Module, and RollApp launches via ILO (Initial Liquidity Offering).
- [KIP 72 - Universal Basic Income](kips/72.md): KIP 72 proposes a Universal Basic Income module aimed at fostering non-sybil network participation (Code of Conduct) through economic rewards.
- [KIP 73 - Fee Reward Distributor v1](kips/73.md): KIP 73 proposes the creation of a Fee Reward Distributor to distribute pooled network fees to active consensus nodes.
- [KIP 74 - Staking Module Part 1](kips/74.md): KIP 74 discusses the implementation of asset staking to consensus nodes on KIRA. This includes delegated staking.
- [KIP 75 - Staking Module Part 2](kips/75.md): KIP 75 discusses the implementation of slashing rules for misbehaving validators and the governance process by which this slashing will be conducted.

### KIP Group 2 - Governance

Coming Soon...

## KIP List

| # | Layer | Title | Key Words |
|---|-------|-------|-----------|
| [71](kips/71.md) | [SEKAI](https://github.com/KiraCore/sekai) | Spending Pools | `staking` `rewards` `distribution` `UBI` |
| [72](kips/72.md) | [SEKAI](https://github.com/KiraCore/sekai) | Universal Basic Income | `UBI` `incentive` |
| [73](kips/73.md) | [SEKAI](https://github.com/KiraCore/sekai) | Fee Reward Distributor v1 | `fees` `rewards` `consensus` |
| [74](kips/74.md) | [SEKAI](https://github.com/KiraCore/sekai) | Staking Module Part 1 | `staking` `delegation` `consensus` `security` |
| [75](kips/75.md) | [SEKAI](https://github.com/KiraCore/sekai) | Staking Module Part 2 | `validators` `slashing` `governance` |

## How to Submit a KIP ? 

### Create your KIP markdown file following these requirements:

- An **Abstract** paragraph, summarizing the proposal. This paragraph must provide a clear understanding of what the KIP is about.
- A **Motivation** paragraph detailing the motivation behind this KIP. Explain why this KIP is necessary or beneficial for the community or project.
- A **Concept and Implementation** description paragraph. The main content section of your file. Provide a comprehensive description of the changes or enhancements you are proposing. Include any relevant details, data, examples, or analyses that support your proposal. This section should be detailed to provide a clear and complete understanding of your KIP to the reviewers and community members.

### Submit your KIP by raising a PR to master:

1. Clone the repository:
```bash
git clone https://github.com/KiraCore/kips.git
cd kips
git fetch --all
git pull
```

2. Create a submission branch with a short name using hyphens (do not number your KIP):
```bash
git branch submission/short-name-of-your-kip
git checkout submission/short-name-of-your-kip
```

3. Add your file to the `kips` folder (do not number your file) and commit:

```bash
cp path/to/file kips/
git add .
git commit -m "your message"
git push
```

You can now raise a [Pull Request](https://github.com/KiraCore/kips/compare/PULL_REQUEST?template=PULL_REQUEST_TEMPLATE.md) and fill in the required form to submit your KIP.

## Contributors

<a align="center" href="https://github.com/KiraCore/kips/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=KiraCore/kips" />
</a>