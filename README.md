# zkMoloch

zkMoloch is a L2 system for [Moloch](https://github.com/MolochVentures/moloch).

The project provides a port of Moloch v2 from Solidity to [Zinc](https://zinc.zksync.io/) with the goal of running on [zkSync](https://zksync.io/).

Using that, all DAO transactions run on zkMoloch leverage the sub-cent gas costs of zkSync L2 transactions, and which have the same security guarantees as L1.

## Original Moloch

The original contract code is:

1. [MolochVentures/moloch-4bc443](https://github.com/MolochVentures/moloch/tree/4bc443f4dad60279b47978fc6987bb978d3dfc58): original version [audited by Consensys](https://consensys.net/diligence/audits/2020/01/the-lao)
1. **[MolochVentures/moloch-72de55](https://github.com/MolochVentures/moloch-72de55374ea583c7b314107e6e17b745f745e875): last version audited by Consensys**
1. [MolochVentures/moloch-4e786d](https://github.com/MolochVentures/moloch/tree/4e786db8a4aa3158287e0935dcbc7b1e43416e38): latest head as of 2021/06/12
1. [Moloch-Mystics/Molochv2.1-ef9473](https://github.com/Moloch-Mystics/Molochv2.1/tree/ef94734a460f00deb61433e225f4be169ad1cc23): latest head as of 2021/06/12

## References

* [Zinc - Minimal example](https://zinc.zksync.io/07-smart-contracts/02-minimal-example.html)
* [Zinc - Troubleshooting](https://zinc.zksync.io/07-smart-contracts/04-troubleshooting.html)
* [Zinc: porting EVM smart contracts to zkSync ZK rollup](https://www.youtube.com/watch?v=y8LlIlCP5eI)


## Tools

* [VSCode Zinc Syntax Highlighting](https://marketplace.visualstudio.com/items?itemName=hedgar2017.zinc-syntax-highlighting)
