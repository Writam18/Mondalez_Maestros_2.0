# MadforCad Supply Chain Optimization

This repository contains analyses and simulation models developed for MadforCad’s supply chain transformation, focusing on Quick Commerce Distributor Engagement and Optimized Production Planning for Gifting SKUs in the Indian chocolate/snacks industry.

## Repository Structure
### File 1 – Distributor Engagement Model : Pilot Run in Mumbai

This section covers a pilot analysis to test distributor-led fulfillment for quick commerce demand spikes.

RDC Allocation and Catchment Areas → Voronoi-based catchment mapping for 25 RDCs.

Distributor Allocation across Mumbai Metropolitan Region → Mapping distributor coverage from RDCs.

Dark Store Distance Analysis → Distance matrix of dark stores from RDC and nearest distributors.

Pilot Run Insight → Business case for allowing distributors to directly cater dark store demand surges, reducing stock-outs and transport cost.


### File 2 – Optimized Production Planning for Gifting Items

This section analyzes different production planning scenarios for assorted/gifting SKUs, aiming to reduce logistics costs and cut lead times.

**Scenario 1 – Baseline**

Optimized allocation across 5 existing co-manufacturing units (Gurgaon, Bhopal, Rajkot, Kolkata, Hyderabad) with existing 6,000 ton capacity each.

**Scenario 2 – Capacity Flexing**

Unconstrained allocation with optimized flexing of the same 5 co-man units beyond 6,000 ton to serve 19 demand centres.

**Scenario 3 – Network Expansion**

Addition of 4 new co-packing units (Mumbai, Bengaluru, Surat, Lucknow) with 6,000 ton capacity each.

Optimized allocation across 9-unit network to reduce supply time and logistics cost.


## Objectives of the Project

+ Improve resilience of MadforCad’s supply chain against Q-com demand spikes.
+ Reduce lead times and costs in distribution of gifting/assorted SKUs.
+ Evaluate feasibility of distributor engagement model vs. existing RDC model.
+ Perform scenario-based production planning optimization for gifting demand (27,000 tons across 19 demand centres).


## Key Insights

+ Distributor Engagement Model can increase net profit during Q-com surges by up to 18% vs. RDC-only model.
+ Optimized Production Planning through decentralized packaging hubs can reduce logistics cost and cut delivery lead time


## Tools & Methods

+ Python (Pandas, Geopandas, PuLP, Matplotlib) for optimization & visualization.
+ Voronoi Diagrams for RDC catchment analysis.
+ Linear Programming for optimal allocation in production planning.
+ Scenario Analysis for cost-benefit benchmarking.



*Author: Writam Mallik*

*Developed as part of MadforCad Supply Chain Strategy Case Study – focused on India FMCG chocolate/snacks distribution challenges*
