# ShadowFox-Data-Science-Internship

# Shadow Fox Internship — Task Overview

This repository contains the tasks completed during the Shadow Fox internship, across Beginner, Intermediate, and Advanced levels.

---

## 🟢 Beginner Level — Visualization Library Documentation

**Objective:** Create a comprehensive documentation guide for 2 Python visualization libraries (chosen from Matplotlib, Seaborn, Plotly, Bokeh, and Pandas), focusing on the variety of graphs each library can generate, with practical code examples.

**Requirements:**
- **Library Overview** — Brief introduction to the selected libraries, their unique features, and typical use cases.
- **Graph Types** — Document the different graph types (line plots, scatter plots, bar charts, histograms, pie charts, etc.), each with a description, use case, and simple code example.
- **Comparison** — Compare the libraries on ease of use, customization, interactivity, and performance with large datasets.

**Libraries used:** Matplotlib, Pandas

---

## 🟡 Intermediate Level — Air Quality Index (AQI) Analysis, Delhi

**Objective:** Conduct an in-depth analysis of the Air Quality Index (AQI) in Delhi, addressing the city's specific environmental challenges. Define research questions around key pollutants, seasonal variations, and geographical factors affecting air quality, using statistical analysis and visualizations to derive insights that can inform air quality improvement and public health strategies.

**Focus areas:**
- Key pollutants affecting AQI
- Seasonal variations in air quality
- Impact of geographical factors on AQI

**Libraries used:** Matplotlib, Pandas, Pyplot

---

## 🔴 Advanced Level — Cricket Fielding Analysis Data Collection

**Objective:** Conduct a detailed fielding performance analysis for 3 players from any innings of a T20 match, to gauge individual fielding contributions and their impact on the team's defensive play.

**Dataset Features:** Match No., Innings, Team, Player Name, Ballcount, Position, Short Description, Pick (clean pick / good throw / fumble / bad throw / catch / drop catch), Throw (run out / missed stumping / missed run out / stumping), Runs, Overcount, Venue.

**Performance Metrics Formula:**
```
PS = (CP × WCP) + (GT × WGT) + (C × WC) + (DC × WDC) + (ST × WST)
     + (RO × WRO) + (MRO × WMRO) + (DH × WDH) + RS
```
Where PS = Performance Score, CP = Clean Picks, GT = Good Throws, C = Catches, DC = Dropped Catches, ST = Stumpings, RO = Run Outs, MRO = Missed Run Outs, DH = Direct Hits, RS = Runs Saved.

**Task Instructions:**
1. Record fielding effort for each ball bowled, per the dataset features above.
2. Prepare the collected data for advanced fielding analysis to identify strengths and areas for improvement.

**Deliverable:** A well-organized spreadsheet/database with the complete fielding data for the match.

**Libraries/tools used:** openpyxl, Seaborn (with try/except blocks used to handle data during execution)

---

## 🛠️ Tech Stack Summary

| Level | Libraries/Tools |
|---|---|
| Beginner | Matplotlib, Pandas |
| Intermediate | Matplotlib, Pandas, Pyplot |
| Advanced | openpyxl, Seaborn |
