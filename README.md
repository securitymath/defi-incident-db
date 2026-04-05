# DeFi Incident Database

Curated database of DeFi security incidents with root cause analysis, attack transaction references, and lessons learned.

Maintained by [Security Math](https://securitymath.com) as part of our ongoing DeFi security research.

## Format

Each incident is documented as a YAML file in `incidents/` with:

```yaml
id: YYYY-MM-PROTOCOL
protocol: Protocol Name
date: YYYY-MM-DD
chain: ethereum | arbitrum | base | ...
loss_usd: 1000000
category: oracle-manipulation | share-inflation | reentrancy | access-control | ...
root_cause: Brief description
references:
  - url: https://...
    title: Source
```

## Statistics (2024-2025)

| Category | Incidents | Total Loss |
|----------|-----------|-----------|
| Oracle Manipulation | 18 | $412M |
| Share/Rate Inflation | 13 | $198M |
| Access Control | 9 | $156M |
| Reentrancy | 7 | $89M |
| Flash Loan Governance | 3 | $35M |
| Bridge Exploits | 4 | $210M |

## Contributing

Found an incident we missed? PRs welcome. Please follow the YAML format above.

## Related

- [Flash Loan Attack Taxonomy (blog)](https://securitymath.com/blog/flash-loan-attack-taxonomy)
- [Slither Custom Detectors](https://github.com/securitymath/slither-custom-detectors)

## License

CC BY 4.0