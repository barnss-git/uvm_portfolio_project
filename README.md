# Production-Grade UVM 1.2 Verification Architecture

This repository contains a modular, constrained-random verification (CRV) testbench implemented in SystemVerilog using the Universal Verification Methodology (UVM 1.2).

## Repository Architecture
- `rtl/`: Synthesizable hardware source files (DUT).
- `tb/`: Verification environment, interfaces, drivers, monitors, sequences, and scoreboards.
- `sim/`: Simulation execution scripts, run directories, and logs.
- `docs/`: Verification plan (vPlan), architectural diagrams, and specifications.
- `scripts/`: Regression runners and automation tools.

## Verification Methodology
- **Language:** SystemVerilog (IEEE 1800-2017)
- **Framework:** UVM 1.2
- **Coverage:** Functional Coverage (Covergroups) & SystemVerilog Assertions (SVA)