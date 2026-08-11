# EE315 Power Systems – Assignment 1

## Economic Selection of Two Heterogeneous Generating Plants

### Student Details

- **Group Number:** 11
- **Member Number:** 4
- **Course:** EE315 – Power Systems
- **Name:** Siri Chandana Kondaparthy

---

## Objective

To develop a generalized MATLAB program to identify the base-load and peak-load plants and determine the operating hours of the peak-load plant for minimum-cost generation.

---

## Assigned Data

| Parameter | Value |
|---|---:|
| Maximum Demand | 511 MW |
| Load Factor | 54% |
| Plant 1 Fixed Cost | Rs 411/kW/year |
| Plant 1 Running Cost | 4 p/kWh |
| Plant 2 Fixed Cost | Rs 501/kW/year |
| Plant 2 Running Cost | 13 p/kWh |

---

## Results

- **Average Demand:** 275.94 MW
- **Annual Energy Requirement:** 2,417,234.40 MWh/year
- **Base-load Plant:** Plant 1
- **Peak-load Plant:** Plant 2
- **Crossover:** -1000 hours/year
- **Peak-load Plant Operating Hours:** 0 hours/year
- **Peak-load Plant Power:** 0 MW

Plant 1 economically dominates Plant 2 because it has both lower fixed cost and lower running cost. Therefore, Plant 2 is not economically dispatched under the minimum-cost solution.

---

## Cost Equations

```text
Plant 1: TC1 = 411 + 0.04H

Plant 2: TC2 = 501 + 0.13H
