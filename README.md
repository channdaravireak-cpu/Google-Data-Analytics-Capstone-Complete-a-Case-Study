# Cyclistic Bike-Share: Rider Behavior & Trend (2026)

**How do annual members and casual riders use Cyclistic bikes differently?**

A data analytics case study for a fictional Chicago bike-share company, Cyclistic. The goal is to understand how annual members and casual riders differ, so the marketing team can design a strategy to convert casual riders into annual members.

**Author:** Daravireak Chann

---

## Business Task

Cyclistic's finance analysts have found that annual members are much more profitable than casual riders. The marketing director believes future growth depends on increasing the number of annual memberships. This project answers the first of three guiding questions:

1. **How do annual members and casual riders use Cyclistic bikes differently?** (this project)
2. Why would casual riders buy annual memberships?
3. How can Cyclistic use digital media to influence casual riders to become members?

## Data

- **Source:** Cyclistic historical trip data (12 months), a public dataset made available by Motivate International Inc. under its published license.
- **Structure:** One record per ride, including start and end time, bike type, and rider type (member or casual).
- **Privacy:** No personally identifiable information is used, so rides cannot be linked to individual riders.
- **Scope:** 6.01 million rides in total (3.90M member, 2.11M casual).

> The raw data files are not included in this repository. Download them from the original source and place them in a `data/` folder.

## Tools

- **Python** (pandas, seaborn, Matplotlib) for cleaning, analysis, and charts
- **Power BI** for the interactive dashboard
- **PowerPoint** for the presentation

## Process

Following the Ask, Prepare, Process, Analyze, Share, Act framework:

1. **Ask:** Define the business task and stakeholders.
2. **Prepare:** Collect the trip data and check its structure and limits.
3. **Process:** Combine files, calculate ride length, day of week, and hour of day, and remove invalid records. *(Edit this step to match exactly what you did.)*
4. **Analyze:** Compare members and casual riders by day of week, ride length, hour of day, and bike type.
5. **Share:** Build the dashboard, report, and presentation.
6. **Act:** Make three data-backed recommendations.

## Key Findings

| Measure | Casual riders | Annual members |
|---|---|---|
| Total rides | 2.11M (35.13%) | 3.90M (64.87%) |
| Average ride length | About 15-21 min | About 11.5-13 min |
| Busiest day | Saturday (about 0.45M) | Tuesday to Thursday (about 0.63M) |
| Hourly pattern | Gradual rise to a 5 PM peak | Peaks at 8 AM and 5 PM |

- **Weekly pattern:** Members take about twice as many rides as casual riders from Monday to Thursday. Casual riding climbs on weekends and peaks on Saturday, nearly matching members.
- **Ride duration:** Casual rides are longer in *time*, especially on weekends. This measures duration, not distance.
- **Hourly pattern:** Members show a commuter-style pattern with two peaks. Casual riders ramp up steadily through the day, which is consistent with leisure use. These are likely explanations, not proven facts.
- **Bike type:** Electric bikes make up 70.39% of all rides (4.23M) and are popular with both groups.

## Recommendations

1. **Launch a weekend membership offer.** Casual rides peak on Saturday.
2. **Show riders what they could save.** Send in-app and email prompts after long rides comparing what they paid with membership cost.
3. **Make e-bikes a member perk.** Offer discounted e-bike unlocks as a headline membership benefit.

## Deliverables

- **Report:** `Cyclistic_Bike-Share_Report.docx`
- **Presentation:** `Cyclistic_Bike_Share_Presentation_Updated.pptx`
- **Dashboard:** `dashboard.pdf`
Daravireak Chann
