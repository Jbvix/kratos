# KRATOS — Open Maritime Prognostics Platform

[![Project Status](https://img.shields.io/badge/status-research%20%26%20development-blue)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)]()
[![Data License: CC0](https://img.shields.io/badge/Data-CC0--1.0-lightgrey)]()
[![Kaggle Benchmark](https://img.shields.io/badge/Kaggle-Benchmark-20BEFF)]()

## Overview

**KRATOS** is an open maritime prognostics platform focused on harbor tug operational readiness, predictive maintenance, mission-aware degradation, and future digital twin research.

> **From Operational Knowledge to Predictive Intelligence.**

## Core Question

**Is this tug ready to safely assume the next maneuver?**

## Main Concepts

- MEKB — Maritime Expert Knowledge Base
- MSI — Mission Severity Index
- MFI — Mission Fatigue Index
- Health Score
- Risk Score
- RUL — Remaining Useful Life
- ORI — Operational Readiness Index
- Mission-Aware Degradation
- Digital Twin Readiness

## Architecture

```text
MEKB -> Maritime Knowledge Graph -> Mission Engine -> Propulsion Engine
-> Health Engines -> ORI Engine -> Simulator -> Machine Learning -> Digital Twin
```

## Public Data Policy

Allowed:
- Synthetic data
- Generic engineering rules
- Normalized parameters
- Anonymized scenarios
- Open mathematical models
- Public documentation

Not allowed:
- Real vessel names
- Company names
- Real operational logs
- Serial numbers
- Proprietary alarm limits
- Internal reports
- Sensitive industrial information

## Roadmap

| Version | Milestone |
|---|---|
| v0.1.0 | Initial Architecture |
| v0.2.0 | Maritime Expert Knowledge Base |
| v0.3.0 | Repository Foundation |
| v0.4.0 | Propulsion Engine |
| v0.5.0 | Mechanical Engine |
| v0.6.0 | Electrical Engine |
| v0.7.0 | Fuel Engine |
| v0.8.0 | Operational Readiness Engine |
| v0.9.0 | Simulator |
| v1.0.0 | First Public Benchmark Release |

## Kaggle Benchmark

https://www.kaggle.com/datasets/jossianbrito/tug-failure-prediction

## Disclaimer

KRATOS is intended for research, education, simulation, and benchmarking. It does not replace certified onboard systems, class rules, manufacturer manuals, or professional maritime decision-making.

## Author

**Jossian Brito**  
Chief Engineer • Maritime Professional • Systems Analyst  
Open Maritime Research Initiative
