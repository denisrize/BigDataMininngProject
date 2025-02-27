# **Impact of the 2023 UCI Points System Modification on Professional Cycling Teams**
![cycling_img](https://github.com/user-attachments/assets/30b6852b-4157-4299-a60a-396618640d64)
## **Project Overview**
This project investigates the impact of the **2023 UCI points system modification** on professional cycling teams. The UCI revised its ranking methodology by redistributing points across different race classifications and expanding team ranking calculations from the **top 10 to the top 20 riders** per team. These changes aimed to encourage broader participation and reduce reliance on a few elite riders.

Using **race results, team rankings, and rider performance data from 2020 to 2023**, this study analyzes how teams of different budget categories adapted their strategies in response to these regulatory changes.

## **Research Questions**
To assess the implications of the UCI modification, this project focuses on four key questions:

1. **Race Participation** – How have teams adjusted their race selection following the increased points distribution?  
2. **Roster Allocation** – Have teams allocated stronger rosters to specific races post-2023?  
3. **Rider Strategy: Star Riders vs. Distributed Effort** – Have teams continued to rely on a few top riders, or have they distributed opportunities across multiple riders?  
4. **Team Rankings and Year-End Points Accumulation** – Have final rankings changed due to the new points distribution? Has the competitive gap between high-budget and low-budget teams widened or narrowed?  

## **Methodology**
- **Data Sources:** This project utilizes publicly available data from [ProCyclingStats](https://www.procyclingstats.com/) and [ProCyclingUK](https://www.procyclinguk.com/) to extract race results, UCI points allocation, rider rankings, and team budgets.
- **Team Roster Strength:** A custom roster strength metric was developed to quantify team competitiveness, giving higher weight to **top-ranked riders while progressively reducing the impact of lower-ranked teammates**.
- **Data Processing:** The dataset includes all **UCI WorldTour and ProTeam race results** from 2020 to 2023, totaling **approximately 7,000 team-race records** after aggregation and filtering.
- **Network Analysis:** A **Team-to-Race Network Graph** was constructed to visualize team participation patterns and roster strength allocation per race.

## **Key Findings**
- **Race Participation:** High-budget teams maintained stable race selection patterns, while low-budget teams shifted toward races with moderate points increases.
- **Roster Allocation:** No clear overall trend emerged, with teams displaying varying strategies in strengthening and weakening their lineups for different races.
- **Rider Strategy:** Low- and medium-budget teams diversified rider participation, reducing reliance on a few star riders, whereas high-budget teams retained a more stable strategy.
- **Team Rankings:** ProTeams, benefiting from flexible race selection, improved their rankings, while low-budget WorldTour teams struggled due to mandatory high-level race participation.

## **Code and Data Availability**
The dataset and analysis code are available in this repository. However, the **web crawler used to extract the data from ProCyclingStats is not included**, as it is part of an ongoing research project for my thesis. My advisor has advised against making it publicly available until the project is completed.

## **Contact**
For questions or collaboration inquiries, please reach out via GitHub or email.
