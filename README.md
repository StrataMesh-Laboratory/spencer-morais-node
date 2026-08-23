# Calhegas Morais Node

Reference **Fog Node** for [StrataMesh Laboratory](https://github.com/StrataMesh-Laboratory).

| Field | Value |
|-------|--------|
| **Node ID** | `FOG-NODE-PT-CM-001` |
| **Name** | Calhegas Morais / Nó de Névoa Calhegas Morais |
| **Locality** | Lisboa, Portugal (~38.7169, −9.1427) |
| **Operator** | André Manuel Calhegas Morais · [AMCM ENI](https://github.com/amcmorais/amcm-eni) |
| **Laboratory** | [StrataMesh-Laboratory](https://github.com/StrataMesh-Laboratory) |
| **Protocol core** | [stratamesh-core](https://github.com/StrataMesh-Laboratory/stratamesh-core) |
| **Portal** | https://calhegasmorais.pt/ |
| **ENI** | https://eni.calhegasmorais.pt/ |
| **Status JSON** | https://status.calhegasmorais.pt/status |
| **Status live** | https://status.calhegasmorais.pt/live |

## What this repository is

Registry and operational description of the **reference node** — identity, holonic role, treasury model, public endpoints, and lab ops pointers.

Protocol implementation lives in **stratamesh-core**. This repo does not duplicate the full worker tree.

## Documents

| Doc | Purpose |
|-----|---------|
| [NODE.md](./NODE.md) | Identity card and live posture |
| [docs/HOLONIC-ROLE.md](./docs/HOLONIC-ROLE.md) | Fog Node inside the holonic stack |
| [docs/TREASURY.md](./docs/TREASURY.md) | `NODE_WALLET` vs user/SCA accounts |
| [docs/ENDPOINTS.md](./docs/ENDPOINTS.md) | Public URLs and guided links |
| [docs/OPS.md](./docs/OPS.md) | Lab operations pointers |
| [config/node.identity.example.json](./config/node.identity.example.json) | Example identity document |

## Lab notice

This node runs **laboratory** infrastructure (`lab: true`). Not production mainnet.
