# MS Excel- Road Accident Analysis Dashboard

## Project Overview
This repository contains a MS Excel dashboard for the Road Transport Department for the year 2021 and 2022.The dashboard analyses the total number of causalities between 2021 and 2022 by vehicle type, road type, and Location/Area.


![Screenshot 2024-10-30 220333](https://github.com/user-attachments/assets/e197549f-31ee-446c-868d-4dc18d3b5a16)



**Data Source**
---
**Road Accident**: The primary dataset "Road Accident" was gotten from the **Road Transport** Department which is recognized as a file extension of .xlsx (spreadsheet) with 12 fields and 3,07 million rows.



**Exploratory Data Analysis**
---
EDA included exploring the dataset to answer the main following task:

- The dashboard analyzes the monthly trend showing comparison of causalities between the year 2021 and 2022.
-	The distribution of causalities by road type.
-	The distribution of causalities by road surface.

**INSIGHTS**
---
- 2021 shows higher casualties across most months compared to 2022.

**Casualty Peaks:**

- 2021: April, July, and October had the highest casualties.
- 2022: Generally lower, but still showed slight increases in April, July, and September.
- December 2022 witnessed a notable drop in casualties, unlike December 2021.

 **DATA SYNOPSIS:**
 
- There was a decline in road casualties from 2021 to 2022, suggesting possible improvement in road safety measures or reduced traffic volume.

**2. Distribution of Casualties by Road Type**
| **Road Type**      | **Casualties** | **Observations**                                          |
| ------------------ | -------------- | --------------------------------------------------------- |
| Single Carriageway | 309.7K         | 🔺 **Highest** — extremely hazardous; needs intervention  |
| Dual Carriageway   | 67.4K          | ⚠️ Significant, but much safer than single carriageways   |
| Roundabout         | 26.8K          | 🔁 Moderate level — possible signage or visibility issues |
| One Way Street     | 7.4K           | 🔽 Low, indicating relatively safer design                |
| Slip Road          | 4.7K           | 🟢 Least risky — likely low volume or better design       |

**DATA SYNOPSIS:**

- Single carriageways account for over 74% of total road-type-related casualties.

**3. Distribution of Casualties by Road Surface**
| **Surface Type** | **Casualties** | **% of Total** | **Insights**                                                                   |
| ---------------- | -------------- | -------------- | ------------------------------------------------------------------------------ |
| Dry              | 279,445        | \~67%          | ⚠️ Most casualties occur on dry roads — likely due to speeding or complacency. |
| Wet              | 115,261        | \~28%          | ⚠️ Slippery surfaces increase accident likelihood.                             |
| Snow/Ice         | Very minimal   | <5% (visually) | ❄️ Rare, possibly seasonal or regional.                                        |

**DATA SYNOPSIS:**

- Majority of casualties occur on dry roads, not wet or snowy, contradicting common assumptions.
- Indicates driver behavior (not poor weather) is the key accident factor.

**EVALUATION**
---
**1. Monthly Casualties Trend: 2021 vs 2022**
**Trend Observation:**

- The line chart shows monthly variations in casualties across both years.
- 2021 consistently recorded higher monthly casualties compared to 2022.
- Peaks for 2021 occurred in:
    - March–April
    - July
    - September–October
- 2022 trend remained relatively stable, with slightly lower values each month:
- Peaks were in May–July, with the highest being July 2022.
- A sharp drop in December 2022, possibly due to seasonal driving caution, fewer travel activities, or safety enforcement.
- Targeted interventions (e.g., speed limits, barriers, awareness) are critical on single carriageways.

**ANALYSIS SUMMARY**

- The overall decline in 2022 suggests:
     - Better traffic management or enforcement
     - Possible policy changes or public awareness campaigns
     - Reduced vehicle usage (economic factors or remote work)
     - However, some months (e.g., July) still remain high-risk in both years, indicating recurring patterns (e.g., holiday traffic, poor weather).

**2. Distribution of Casualties by Road Type**

-This breakdown highlights how different road infrastructures contribute to accident casualties:

| **Road Type**          | **Casualties** | **% Contribution (approx.)** | **Interpretation**                                                                       |
| ---------------------- | -------------- | ---------------------------- | ---------------------------------------------------------------------------------------- |
| **Single Carriageway** | 309,700        | \~74%                        | ⚠️ Highly prone to accidents due to two-way traffic, limited barriers, and narrow lanes. |
| **Dual Carriageway**   | 67,400         | \~16%                        | Safer than single, but still vulnerable — likely due to speeding.                        |
| **Roundabout**         | 26,800         | \~6%                         | Medium risk — confusion, congestion, or visibility could be causes.                      |
| **One-Way Streets**    | 7,400          | \~1.7%                       | Safer by design; fewer head-on collisions.                                               |
| **Slip Roads**         | 4,700          | \~1.1%                       | Very low — indicates effective entry/exit control systems.                               |

**ANALYSIS SUMMARY**

- Single carriageways are the most dangerous — contributing to 3 out of every 4 casualties.
- Investment in dualizing major single carriageways or adding traffic calming measures could save thousands of lives.

**3. Distribution of Casualties by Road Surface Condition**

- Understanding surface conditions helps target accident prevention efforts:
  
| **Road Surface** | **Casualties**        | **Approx. %** | **Interpretation**                                                                               |
| ---------------- | --------------------- | ------------- | ------------------------------------------------------------------------------------------------ |
| **Dry**          | 279,445               | \~67%         | 🚘 Most accidents occur on dry roads, possibly due to speeding, distractions, or overconfidence. |
| **Wet**          | 115,261               | \~28%         | 🌧️ High traction loss, but still less than dry conditions.                                      |
| **Snow/Ice**     | Minimal (Not labeled) | <5%           | ❄️ Rare in occurrence but potentially severe when they do happen.                                |

**ANALYSIS SUMMARY**

- Contrary to expectations, more accidents happen on dry roads.
- This implies that driver behavioral factors (speeding, phone use, fatigue) are more critical than weather conditions.
- However, wet roads still present significant danger and require signage, drainage, and surface improvements.

**DATA DRIVEN DECISIONS**
| Area                     | Observation                                                          | Recommendation                                                           |
| ------------------------ | -------------------------------------------------------------------- | ------------------------------------------------------------------------ |
| Monthly Trends           | 2022 saw improvements, but certain months (e.g., July) remain risky. | Launch seasonal road safety campaigns.                                   |
| Road Type Casualties     | Single carriageways dominate accident zones.                         | Upgrade to dual roads or install speed enforcement and rumble strips.    |
| Road Surface Conditions  | Accidents happen more on dry roads.                                  | Public education on safe driving even in “ideal” conditions.             |
| Urban vs Rural (Sidebar) | More casualties occur in **urban** areas (255.9K vs. 162K).          | Increase enforcement in congested urban areas.                           |
| Time of Day (By Light)   | Majority (304,963) happen during **daylight** hours.                 | Daylight does not guarantee safety — distractions and congestion matter. |

**Technical Stack**
---
- 	Data Cleaning –MS Excel
- 	Data Processing–MS Excel
- 	Data Analysis–MS Excel
- 	Data Visualization–MS Excel
- 	Report/ Dashboard–MS Excel


