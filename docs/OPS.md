# Lab operations — pointers

Detailed scripts and workers live in **stratamesh-core**.

```bash
git clone https://github.com/StrataMesh-Laboratory/stratamesh-core.git
cd stratamesh-core
./scripts/run_fog_node.sh          # local lab node processes
./scripts/publish_loop.sh          # optional publish loop
cd src && python3 mesh_doctor.py   # self-check
cd src && python3 protocol_benchmark.py
```

## Live health

- Status aggregation: `https://status.calhegasmorais.pt/status`
- AIOps cycle (when enabled): worker `/cycle` or `/last` under AIOps service
- Upstream flags in status: token, dag, agora, republic, auth, aiops, holons, …

## Change discipline

1. Normative docs in core before silent behaviour change.  
2. Lockstep: git + live workers/D1 when public copy or endpoints move.  
3. Keep `NODE_WALLET` language out of “Conta” / user-account UI.
