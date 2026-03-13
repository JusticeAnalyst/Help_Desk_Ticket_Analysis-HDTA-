# Help_Desk_Ticket_Analysis-HDTA-
### Power BI Dashboard — Operational Efficiency & Process Improvement

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)


##  Project Overview
A 4-page interactive Power BI dashboard analyzing **37,000+ help desk tickets** 
across **7 years (2016–2023)** to identify operational bottlenecks, 
agent performance issues, and resolution inefficiencies.

This is **Project 2 of 4** in my Business Data Analysis Portfolio Series.


##  Dashboard Pages

| Page | Title | Focus |
|------|-------|-------|
| 1 | Cycle Time & Resolution Efficiency | How fast are tickets resolved? |
| 2 | Bottleneck Identification | Where do tickets get stuck? |
| 3 | Agent Performance & Workload | How efficient are agents? |
| 4 | Volume & Trend Analysis | How has ticket volume changed? |


##  Key Findings

1. **Open State is the #1 Bottleneck** — Tickets spend avg **818hrs (~34 days)** 
   in Open state before being actioned
2. **Critical Escalation Rate** — **50.4%** of all tickets escalated, 
   every high-volume project at 96–100% escalation rate
3. **Resolution Time Surged in 2023** — 2023 avg (1,775hrs) is **6x worse** 
   than 2022 (299hrs) as volume hits all-time peak
4. **Workload Imbalance** — **15.5%** unassigned tickets, 
   top agent handles 2.5x more than average
5. **Rework & Looping** — Tickets cycle back through In Progress 
   **0.83 times** on average
6. **Lowest Priority Neglected** — Lowest priority tickets take 
   **1,900+ hrs** to resolve
7. **Triage Improved After 2018** — Unknown priority dropped from 
   **82.8% to 0%** from 2019 onwards

##  Recommendations

1. **Implement Auto-Assignment Rules** — Eliminate 15.5% unassigned backlog
2. **Set Open State SLA of 48hrs** — Flag tickets exceeding threshold
3. **Redefine Escalation Criteria** — Target <20% escalation rate
4. **Balance Agent Workload** — Cap max tickets per agent
5. **Dedicate Resources to 2023 Backlog** — Resolution rate dropped to 75%


##  Tools & Technologies

- **Power BI** — Dashboard development & visualization
- **DAX** — Calculated columns, measures & time intelligence
- **Python** — Custom visual for workflow bottleneck chart
- **Data Modeling** — Multi-table relationships & star schema

##  Dataset
- **Source:** Help desk ticket system export
- **Tables:** issues_snapshot, issues, issues_change_history, Scored_sample
- **Records:** 37,000+ tickets
- **Period:** January 2016 — March 2023


## Connect With Me
[![LinkedIn](www.linkedin.com/in/justice-analyst)
[![GitHub](https://github.com/JusticeAnalyst)

*Part of the Business Data Analysis Portfolio Series*
*2 of 4 Projects Complete*


