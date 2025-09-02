# 2026 IEEE MOVE Truck Data Science Challenge

## Overview
Plan ahead! The **IEEE MOVE Truck Data Science Challenge for 2026** is a competition focused on leveraging disaster-response telemetry for resilient network engineering. Participants will analyze geospatial signal data collected by IEEE MOVE Trucks to identify faulty towers and propose efficient network layouts. This challenge combines anomaly detection, geospatial analysis, and resource optimization to enhance disaster response strategies.  

The **2026 Data Science Challenge** official announcement will take place at the **2025 WF-PST**!  

Learn more about the [IEEE MOVE GLOBAL program](#).  

---

## Eligibility
- **Participants**: The competition is open to individuals and teams worldwide. Participants must register by the deadline and agree to the terms and conditions.  
- **Team Composition**: Teams can consist of up to four members.  
- **Age Requirement**: All participants must be at least 18 years old.  

---

## Judges
- **Judging Panel**: The competition will be judged by a panel of experts in data science, telecommunications, and disaster response. Judges will include representatives from IEEE, telecommunications companies, and disaster relief organizations.  
- **Judging Criteria**:  
  - **Anomaly Detection Accuracy**: Precision and recall for identified faulty towers, validated against ground-truth maintenance logs.  
  - **Optimization Plan Efficacy**: Coverage area per dollar of infrastructure cost, signal strength compliance, and reduction in tower count compared to the baseline.  

---

## Competition Phases

### Pre-Conference Phase
- **Challenge Announcement and Registration**: Sep 23, 2025 – Jan 31, 2026  
- **Testing Dataset Release**: Feb 1, 2026  
- **Finalist Selection**  
  - **Final Dataset Release**: Mar 1, 2026  
  - **Solution Development**: Mar 1 – May 31, 2026  
  - **Results Submission**: Jun 1, 2026  
  - **Evaluation of Submissions**: Jun 1 – Jun 13, 2026  
  - **Announcement of Finalist Teams**: Jun 16, 2026  

### Conference Phase (September 22–24, 2026)
- **Day 1**: Challenge overview, working session, and progress check-in.  
- **Day 2**: Final development, solution submission, and presentation preparation.  
- **Day 3**: Finalist presentations, awards ceremony, and closing remarks.  

---

## Dataset Description
For the IEEE MOVE Truck Data Science Challenge, the dataset will be derived from log files collected by cellular routers deployed on the trucks. These log files will contain signal metrics for both AT&T and Verizon networks, including:

- **RSSI (5G/4G)**: Received Signal Strength Indicator, which measures the overall signal strength, including both usable signal and noise.  
- **RSRP (5G/4G)**: Reference Signal Received Power, which measures the usable downstream signal strength specifically for 4G LTE networks.  
- **SINR (5G/4G)**: Signal-to-Interference-plus-Noise Ratio, which indicates how much of the signal is usable compared to noise and interference.  

### Dataset Collection
The dataset was collected from IEEE MOVE Truck deployments, which gather geospatial data using GPS-tracked signal metrics across AT&T and Verizon networks. This data will be helpful for identifying faulty towers and optimizing network layouts during disaster response scenarios.  

---

## Problem Statements

### Faulty Tower Detection
- Detect sudden signal drops using statistical thresholds.  
- Identify towers with abnormal idle periods.  
- Compare historical RSRP/RSSI distributions against real-time data.  

### Coverage Optimization
- Propose tower placements to maximize coverage while minimizing costs.  
- Consider signal overlap, terrain modeling, demand hotspots, and tower sharing feasibility.  

---

## Submission Requirements
- **Project Report**: Maximum 10 pages.  
- **Failed Towers**: CSV file with Tower IDs, failure timestamps, and anomaly type.  
- **Optimization Proposal**:  
  - GeoJSON file of proposed tower locations.  
  - Cost-benefit analysis (CAPEX vs coverage gain).  
  - Heatmaps comparing existing vs proposed signal strength.  

---

## Evaluation Criteria
- **Anomaly Detection Accuracy**  
- **Optimization Plan Efficacy**  

---

## Prizes and Recognition
- **Finalist Presentation**: Finalists will present their solutions at the **2025 IEEE World Forum on Public Safety Technology**.  
- **Awards Ceremony**: Winners will be recognized during the awards ceremony on **September 25, 2025**.  

---

## Additional Details
- **Participation Benefits**: Participants will contribute to enhancing disaster response strategies and have the opportunity to network with industry experts.  
- **Registration Process**: Registration will be available online through the IEEE website. Participants must provide their IEEE membership number (if applicable) during registration.  

---

## Contact Information
Please contact **Dr. Jian Tao** at [jtao@tamu.edu](mailto:jtao@tamu.edu) if you have any questions.  
