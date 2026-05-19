# Energy Transition Scenario Analysis

## Overview
This project models electricity sector emissions under a baseline scenario and a clean energy policy scenario. It demonstrates how shifts in energy generation mix (coal, natural gas, renewables) influence emissions outcomes over time.

The analysis is designed as a simplified analogue to large-scale energy-economic modeling frameworks such as power sector dispatch and CGE models used in climate policy research.

## Research Question
How does accelerated renewable energy deployment and coal phaseout affect total CO₂ emissions and emissions intensity over time?

## Methods
- Constructed a stylized electricity generation dataset (2020–2030)
- Applied emissions factors by generation source
- Built baseline and policy counterfactual scenarios
- Computed total emissions and emissions intensity
- Visualized comparative scenario outcomes

## Key Assumptions
- Linear transitions in generation mix
- Constant emissions factors over time
- No price feedbacks or demand elasticity
- Partial equilibrium framework

## Key Findings
- Accelerated renewable deployment significantly reduces emissions over time
- Coal phaseout is the primary driver of decarbonization
- Emissions intensity declines more sharply under policy scenario

## Tools Used
- Python (pandas, numpy, matplotlib)
- Scenario analysis & policy modeling
- Data visualization

## Project Structure
See `/src` for modular scripts and `/notebooks` for full analysis workflow.

## Outputs
- Scenario comparison plots
- Emissions summary tables
- Technical memo (see `/docs`)

## Author
Josie McGuire, MPH
