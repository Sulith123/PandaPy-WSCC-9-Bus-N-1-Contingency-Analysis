# PandaPy – WSCC 9-Bus N−1 Contingency Analysis

**Pandapower** is an open-source Python library used for power system analysis, including load flow, short-circuit, and optimal power flow studies.

More information about pandapower can be found on its official website.

## Project Description

In this project, the **WSCC 9-bus test system** is modeled using **pandapower**, and an **N−1 contingency analysis** is performed to evaluate system performance under various outage conditions.

The following contingency scenarios are analyzed:

* Loss of a transmission line
* Loss of a generator
* Loss of a transformer

## Validation

All simulation results obtained from pandapower are **verified using PSS®E version 33**.
The **Full Newton–Raphson method** is used as the power flow solver in PSS®E to ensure accurate comparison.

## Repository Contents

This repository contains:

* 📓 **Jupyter Notebook** with the pandapower simulations
* ⚙️ **PSS®E files** used for validation
* 📄 **PDF report** with a detailed comparison of pandapower and PSS®E results

## Results

The final comparison of results between pandapower and PSS®E can be found in the attached **PDF report**, demonstrating close agreement between the two tools.

## Tools Used

* Python (pandapower)
* PSS®E 33
* Jupyter Notebook
