# Treasury model — NODE_WALLET

## Rule

The Fog Node holds a **treasury wallet** (`NODE_WALLET`).  
It is **not** an account-holding retail entity.

```
TRD poles (#mint / #0)
  ≠ Fog wallet (NODE_WALLET)
  ≠ user / SCA account wallets
```

## Poles

| Address | Role |
|---------|------|
| `#mint` | Emit-only via Proof of Contribution |
| `#0` | Burn sink on resource use |
| Wallets | Circulation — including node treasury and agent wallets |

## Lab classes (when present in monetary views)

- `lab_only` — laboratory STRATA; not transit-eligible by default  
- `transit_eligible` — stricter path; rare in pure lab posture  

Authoritative numbers: `GET` monetary / status pulse on the live node — not this document.
