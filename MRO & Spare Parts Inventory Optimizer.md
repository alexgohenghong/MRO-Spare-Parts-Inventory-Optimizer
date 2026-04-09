MRO & Spare Parts Inventory Optimizer
Project Overview
This project presents a data-driven inventory optimization model for Maintenance, Repair, and Operations (MRO), specifically targeting high-value avionics and aerospace manufacturing components. By applying Lean Operations principles and statistical modeling, this tool dynamically calculates safety stock levels to prevent Aircraft on Ground (AOG) situations while significantly reducing unnecessary capital tied up in the warehouse.

Key Features
AOG Risk Mitigation: Ensures a 95% service level for critical spare parts, preventing costly production halts or flight delays.

Capital Tie-Up Reduction: Replaces legacy "rule-of-thumb" buffering with precision statistical forecasting, successfully freeing up over 15% of working capital.

Dynamic Reordering: Automatically generates Reorder Points (ROP) based on supplier lead times and demand volatility.

Core Methodology & Logic

The optimization engine is built upon fundamental Operations Management (OM) formulas:

1. Dynamic Safety Stock Calculation
Calculates the exact buffer needed to cover demand fluctuations during the supplier's lead time.

Safety\_Stock = Z \times \sqrt{L} \times \sigma_d

(Where $Z$ is the service level factor, $L$ is Lead Time, and $\sigma_d$ is the standard deviation of demand).

2. Reorder Point (ROP)

ROP = (\bar{d} \times L) + Safety\_Stock

(Where \bar{d}is average demand).

Results & Analytics:
Based on a simulation of 50 high-value avionics SKUs:

Legacy Capital Tied Up: Baseline metric using static 3-month buffering.

Optimized Capital Tied Up: Result of the Z-score dynamic safety stock model.

Impact: Achieved a significant reduction in capital tie-up (15%+), translating to millions of dollars in released cash flow for high-volume manufacturing environments.


Tech Stack
Language: Python (Pandas, NumPy)

Domain Expertise: Supply Chain Analytics, Lean Manufacturing, DMAIC Framework, Root Cause Analysis (RCA).

Author
Goh Eng Hong (Alex)
Bachelor of Applied Business Analytics (Honours) student at TAR UMT (Penang Branch).Expected Graduation: June 2027.Passionate about Aviation Safety, Predictive Modeling, and Operational Excellence (OpEx).
Contact: alexgohenghong@gmail.com


