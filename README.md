<div align="center">

# Enhancing FANET Communication Reliability Using OLSR-PSO-GA Optimization

**Optimized OLSR MPR selection using Particle Swarm Optimization and Genetic Algorithms for reliable UAV networks.**

![Status](https://img.shields.io/badge/status-research%20in%20progress-orange)
![Simulator](https://img.shields.io/badge/simulator-ns--3-blue)
![Language](https://img.shields.io/badge/language-C%2B%2B-00599C)
![Protocol](https://img.shields.io/badge/protocol-OLSR-green)
![License](https://img.shields.io/badge/license-MIT-lightgrey)

</div>

---

## 📌 Overview

Flying Ad Hoc Networks (FANETs) are characterized by high node mobility,
frequent topology changes and unstable wireless links. Under these conditions,
the standard **OLSR** protocol may select Multipoint Relays (MPRs) that are
not reliable enough, which degrades communication quality.

This research project proposes an **optimized MPR selection mechanism** that
combines **Particle Swarm Optimization (PSO)** and a **Genetic Algorithm (GA)**
to improve the reliability of UAV communications, while preserving the
fundamental principles of the OLSR protocol.

## 🎯 Objectives

- Improve communication reliability in dynamic UAV networks
- Optimize MPR selection using a hybrid PSO-GA approach
- Reduce packet loss and end-to-end delay
- Maintain compatibility with the OLSR protocol architecture
- Evaluate performance through realistic ns-3 simulations

## 🏗️ System Architecture

<div align="center">

![System Architecture](docs/images/architecture.png)

*Figure 1: Overall architecture of the proposed OLSR-PSO-GA approach.*

</div>

## 🔄 Methodology

<div align="center">

![Workflow](docs/images/workflow.png)

*Figure 2: Workflow of the optimized MPR selection process.*

</div>

The proposed approach follows these main steps:

1. **Neighbor discovery**: OLSR nodes exchange HELLO messages.
2. **Metric evaluation**: link quality and network conditions are assessed.
3. **Hybrid optimization**: PSO and GA search for the best MPR set.
4. **MPR selection**: the optimized set replaces the default selection.
5. **Routing**: topology control and route computation proceed as in OLSR.

## 🛠️ Technologies

| Category | Tools |
|----------|-------|
| Simulator | ns-3 |
| Language | C++ |
| Routing protocol | OLSR |
| Optimization | Particle Swarm Optimization (PSO), Genetic Algorithm (GA) |
| Application domain | FANET / UAV networks |

## 📊 Evaluation Metrics

- Packet Delivery Ratio (PDR)
- End-to-End Delay
- Throughput
- Routing Overhead
- Packet Loss Rate

## 📈 Results

### Packet Delivery Ratio

<div align="center">

![PDR](docs/images/result-pdr.png)

*Figure 3: PDR comparison between standard OLSR and OLSR-PSO-GA.*

</div>

### End-to-End Delay

<div align="center">

![Delay](docs/images/result-delay.png)

*Figure 4: End-to-end delay comparison.*

</div>

### Throughput

<div align="center">

![Throughput](docs/images/result-throughput.png)

*Figure 5: Throughput comparison.*

</div>

### Summary

| Metric | Standard OLSR | OLSR-PSO-GA | Improvement |
|--------|---------------|-------------|-------------|
| PDR | — | — | — |
| End-to-End Delay | — | — | — |
| Throughput | — | — | — |

## 🚧 Project Status

This project is part of ongoing academic research.
The implementation and detailed experimental data are **not publicly
available yet** and will be released after the associated publication.

- [x] Problem definition and state of the art
- [x] Proposed architecture
- [x] Simulation and evaluation
- [ ] Journal / conference publication
- [ ] Public release of the implementation

## 📚 Citation

If you refer to this work, please cite:

```bibtex
@misc{olsr_pso_ga_fanet,
  title  = {Enhancing FANET Communication Reliability Using OLSR-PSO-GA Optimization},
  author = {Your Name},
  year   = {2026},
  note   = {Research project}
}
```

## 👤 Author

**Your Name**
PhD Student, Your University / Laboratory
📧 your.email@example.com
🔗 [LinkedIn](https://linkedin.com/in/your-profile) · [Google Scholar](#) · [ResearchGate](#)

## 📄 License

This project is released under the MIT License. See the `LICENSE` file for details.
