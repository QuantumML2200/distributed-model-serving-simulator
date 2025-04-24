# Distributed Model-Serving Simulator

## Objective
Simulate realistic scenarios for serving large language model (LLM) inference across distributed (edge/cloud) environments with heterogeneous compute resources.

## Motivation
- Understand and optimize latency, throughput, and cost for AI inference.
- Benchmark and compare scheduling strategies.
- Leverage my background in quantum optimization to propose novel AI workload scheduling methods.

## Key Components
- Heterogeneous compute nodes (configurable CPU/GPU)
- Realistic request generation and token streaming
- Scheduling policies (round-robin, least-loaded, cost-aware, quantum-inspired)
- Metrics (latency percentiles, GPU utilization, tokens per second)
- Interactive dashboard for visualization

## Tech Stack
- Python 3.11+
- Ray / Dask for distributed simulation
- NumPy, Pandas, YAML
- Streamlit / Plotly for visualization 

## Roadmap
| Phase | Description | Status |
|-------|-------------|--------|
| 0 – Prep | Define project specs clearly | (in-progress) |
| 1 – Baseline Simulator | Single-node stub | (TBD) |
| 2 – Topology Simulation | Heterogeneous nodes |  |
| 3 – Workload Generation | Realistic traces |  |
| 4 – Scheduling Policies | Implement and compare |  |
| 5 – Metrics & Visualization | Dashboard creation |  |
| 6 – Experiments | Case studies |  |
| 7 – Polish & Share | Blog and cleanup |  |

## How to Run (Coming Soon)
(Instructions will be added as the project evolves.)

## Author
**Zecheng Li**  
CS PhD Student, Penn State University  
[zxl5523@psu.edu](mailto:zxl5523@psu.edu)
