# Tray Allocation MILP

This project contains Pyomo mixed-integer linear programming models for assigning trays to lanes under lane-capacity constraints.

## Contents

- `MILP_model_Q4.ipynb`: model exploration and CSV export for the smaller tray instance.
- `MILP_model_Q6.ipynb`: bin-packing style MILP that minimizes the number of used lanes.
- `data/`: JSON tray instances.
- `outputs/`: generated CSV assignment outputs.

## Setup

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

The notebooks use Pyomo with the CBC MILP solver.
