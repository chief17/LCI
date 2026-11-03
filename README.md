# LCI: Local Criticality Indicator

Code and data for the paper:

> **Decentralized Local Criticality Indicators for Proactive Vulnerability Detection in Energy-Constrained IoT Edge Mesh Networks**
> Nihit Mohan Johari, K. K. Pattanaik, Vinal Patel.
> *Computer Networks* (Elsevier). Citation details will be added on publication.

LCI lets each node of a battery-powered wireless mesh estimate the consequence and urgency of its own failure from periodic 1-hop gossip. It combines a 2-hop bypass-aware structural fragmentation indicator, a workload concentration indicator, and an energy-based failure probability into one bounded risk score.

## Status

This repository is being prepared. The contents listed below will be added here.

## Planned contents

| Folder | Contents |
|---|---|
| `generators/` | Seeded generators for the four topology families and the per-node workload of Experiment 2 |
| `analytical/` | Experiments 1 and 2: Spearman correlation and Average Precision, scalability sweeps, confidence intervals and paired tests |
| `traces/` | Recorded per-node traces of the emulation runs of Experiment 3 (G1 and G4, with and without mitigation) |
| `analysis/` | Offline replay of the traces: sensitivity to the alert threshold, lookahead horizon and drain-rate uncertainty; runtime ground-truth construction; node-level bootstrap |
| `figures/` | Scripts that reproduce the figures and tables of the paper |

## Reproducing the results

Instructions, software versions and expected outputs will be documented here, with one command per table and figure.

## Citation

A BibTeX entry will be added on publication.

## License

To be added.

## Contact

Nihit Mohan Johari, ABV-Indian Institute of Information Technology and Management Gwalior, India.
