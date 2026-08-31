# Production-System Simulation & Validation in AnyLogic

A **team university project** modeling a brewery production system from fermentation through packaging using AnyLogic and a structured simulation methodology.

> **Important:** the original `.alp` AnyLogic model was not included in the files currently available to me, so this repository is prepared as a case-study shell. Add the `.alp` file before making this a pinned technical repository if you still have it.

## Problem

The simulated production line faced rising demand. The objective was to identify bottlenecks, test operational changes, and improve performance before committing to additional capacity.

## Approach

- Defined the system, assumptions and SMART KPIs
- Built a conceptual process model and translated it into AnyLogic
- Modeled queues, resources, delays, cleaning logic, routing and downtime
- Performed **verification** to check that the simulation behaved as intended
- Performed **validation** against the real-world process assumptions/data used in the case
- Ran preliminary and final experiments to test bottleneck-removal strategies

## KPIs

- Resource utilization
- Production throughput
- Average cycle time
- Average queue time

## Selected findings

The baseline analysis identified the bottling machine as the largest queue bottleneck, followed by cooling. Experiments tested production-plan changes and resource-capacity changes, including additional bottling/cooling capacity.

## Industry 4.0 extension

The project also explored how real-time sensor data could support:

- predictive maintenance;
- anomaly detection;
- quality control;
- dynamic resource allocation;
- more flexible production planning.

## Tech / methods

`AnyLogic` · `Discrete-Event Simulation` · `Verification & Validation` · `Experimental Design` · `KPI Analysis` · `Industry 4.0`

## Attribution

This was a team project completed with **Henrik Anthony Svensson**. Keep that attribution in the public repository and only upload the shared report/model if you are comfortable publishing the collaborative work.

## Recommended files to add

If you still have them, add:

```text
model/
  LibertyBrew_Simulation.alp
assets/
  model-overview.png
  bottleneck-results.png
  experiment-results.png
```

Once the `.alp` file is added, this becomes a strong portfolio repo because reviewers can see the actual model rather than only a written case study.
