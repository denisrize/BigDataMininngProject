 <table>
  <tr>
    <td>
      <h1>Impact of the Points System Modification on Professional Cycling Teams Strategy</h1>
    </td>
    <td>
      <img src="https://github.com/user-attachments/assets/30b6852b-4157-4299-a60a-396618640d64" alt="cycling_img" width="200"/>
    </td>
  </tr>
</table>

## **Project Overview**
This project investigates the impact of the **2023 UCI points system modification** on professional cycling teams. The UCI revised its ranking methodology by increasing points across the prestigious races of the racing season, and expanding team ranking calculations from the **top 10 to the top 20 riders** per team. These changes, which will serve to widen the gap between the points scored in the most prestigious races and those in lower categories, are aimed at encouraging teams to enter their best riders in the most important races and to ensure a better correlation between the points awarded and the sporting achievement involved, which is clearly at a higher level in UCI WorldTour races featuring all UCI WorldTeams.

Furthermore, the UCI World Ranking for teams, which up until now has been determined by the total points obtained by the best 10 riders in each team, will now be calculated on the basis of the results of the best 20 riders (which corresponds to the minimum number of riders for UCI ProTeams).

This increase in the number of riders is designed not only to better reflect the competitive strength of the teams but also to reduce the downside of their best riders being unavailable for any reason (for example, injury or illness) during a given season. For further details, read this [article](https://www.uci.org/pressrelease/modification-of-points-scale-for-mens-events-in-uci-international-road/2YPy6zPPse6w8c5s9J0dKd)
 
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

![new_vs_abonded](https://github.com/user-attachments/assets/0db17dee-9be4-4a6b-9192-2b83cb90f484)
![world_participation_eu](https://github.com/user-attachments/assets/b8279a90-6710-4079-af59-c96c518e3012)

(Blue represent **higher** budget teams)

- **Roster Allocation:** No clear overall trend emerged, with teams displaying varying strategies in strengthening and weakening their lineups for different races.
![roster_strength](https://github.com/user-attachments/assets/c08ef181-3371-4840-9a96-cbe6609f0cc9)
                          <img src="https://github.com/user-attachments/assets/1676a05e-eb75-47fa-ad4b-f79693edfd03" alt="graph" width="600"/>

- **Rider Strategy:** Low- and medium-budget teams diversified rider participation, reducing reliance on a few star riders, whereas high-budget teams retained a more stable strategy.
![riders_participation_internal_rank](https://github.com/user-attachments/assets/8b4b1b0d-0302-49b4-b8c9-ff9b859aa623)
![riders_participation_leader_score](https://github.com/user-attachments/assets/6bc3b591-0d6a-4d63-ae24-f0f78ebff9ad)

- **Team Rankings:** ProTeams (subcategory inside low-budget teams), benefiting from flexible race selection, improved their rankings, while low-budget WorldTour teams struggled due to mandatory high-level race participation (hence the large variability in final ranking).
<img src="https://github.com/user-attachments/assets/240d1f70-8d67-455b-a55b-ce3685f93002" alt="points" width="500"/>
<img src="https://github.com/user-attachments/assets/ab22c297-fa83-4897-8b5b-45abed81cbec" alt="ranking" width="500"/>

## **Code and Data Availability**
The dataset and analysis code are available in this repository. However, the **web crawler used to extract the data from ProCyclingStats is not included**, as it is part of an ongoing research project.

## **Contact**
For questions or collaboration inquiries, please reach out via GitHub or email.
