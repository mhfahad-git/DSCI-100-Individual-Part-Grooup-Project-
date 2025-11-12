# Minecraft Game Usage Prediction (DSCI 100 – Individual Planning Report)

**Author:** MH Fahad  
**Course:** DSCI 100 – Introduction to Data Science  
**Instructor:** Eugenia Yu  
**Group:** 33  
**Repository:** `minecraft_game_report_grp33`

---

## 📘 Project Overview

This repository contains my **Individual Planning Report** for the DSCI 100 group project, based on data from a **Minecraft Research Server** operated by UBC Computer Science.  
The project explores player and session data to understand gameplay behavior and plan predictive methods for future analysis.

I focus on **Question 3** from the project prompt:  

> “When are large numbers of simultaneous players most likely to occur?”

This question supports **demand forecasting**, helping ensure the server has enough capacity for active players.

---

## 📂 Files Included

| File | Description |
|------|--------------|
| `minecraft_game_report_grp33.ipynb` | Main Jupyter Notebook containing all code, analysis, and explanations. |
| `minecraft_game_report_grp33.html` | Exported HTML version for submission to Canvas. |
| `players.csv` | Dataset describing unique players and their characteristics. |
| `sessions.csv` | Dataset describing individual play sessions. |
| `README.md` | Overview and setup instructions for this repository. |

---

## 🧮 Steps Performed in Notebook

1. Load and clean data using `tidyverse` and `janitor`.  
2. Compute summary statistics for the `players.csv` dataset.  
3. Produce **two exploratory visualizations**:  
   - Session count heatmap (weekday × hour).  
   - Session duration distribution.  
4. Formulate a specific predictive question.  
5. Propose one modeling method (e.g., regression or KNN) and explain why it fits.

---

## ⚙️ How to Run

1. Open `minecraft_game_report_grp22.ipynb` in **JupyterLab**.  
2. Run all cells in order.  
3. Required packages:  
   `tidyverse`, `janitor`, `skimr`, `GGally`, `lubridate`, `knitr`, `kableExtra`  
4. All outputs (tables + plots) will appear inline.

---

## 🧾 Submission Information

- Submit both the `.ipynb` and `.html` versions to **Canvas**.  
- GitHub repo must include at least **five commits** with meaningful messages.  
- File names must include your **group number (22)**.

---

© 2025 MH Fahad — University of British Columbia
