# FIFA World Cup Analysis & 2026 Prediction Engine

## Project Overview

This project analyzes FIFA World Cup history from 1930–2022 and builds a machine learning-based prediction engine for the 2026 FIFA World Cup.

The project combines data cleaning, exploratory data analysis, feature engineering, machine learning, Monte Carlo simulation, and interactive Tableau dashboards to uncover historical trends and forecast future tournament outcomes.

---

## Technologies Used

* Python
* Pandas
* NumPy
* SQL
* Scikit-Learn
* SHAP
* Tableau
* Git & GitHub

---

## Project Workflow

### 1. Data Collection
### 2. Data Cleaning (SQL + Python)
### 3. Exploratory Data Analysis - ## Key Findings

##### a. Historical Analysis (1930–2022)
- **Brazil, Germany and Italy** account for **62% of all World Cup titles** across 22 tournaments
- **Host nations** have won the tournament **27% of the time** but **73% of hosts** reached at least the quarter-finals, confirming a clear home advantage
- **Goals per game peaked at 5.38 in 1954** and have declined to a modern average of 2.5, reflecting the evolution of defensive tactics
- **CONMEBOL and UEFA** have won **100% of all World Cups** despite CAF (Africa) having 54 member nations, no African team has ever won
- Home win rate across all international matches is **~46%**, dropping to ~40% at neutral WC venues
- Being ranked **#1 by FIFA before the tournament** does not reliably predict the winner upsets are statistically common

### b. WC 2026 Prediction (Monte Carlo Simulation)
- **Argentina** is the predicted most likely winner at **21.35% probability** across 10,000 simulations
- **France** ranks 2nd at **19.35%**
- The model uses match-level prediction trained on 43,000+ historical international matches, simulating the complete 48-team bracket match by match

### 4. Historical World Cup Insights
### 5. Feature Engineering
### 6. Machine Learning Model Development
### 7. Monte Carlo Tournament Simulation
### 8. Interactive Dashboard Creation

---

## Tableau Dashboards

### 1. FIFA World Cup Historical Analysis

* World Cup Titles by Country
* Winners Timeline
* Host Nations

### 2. Top 4 Consistency Analysis

* Top 4 Appearances
* Top 4 Breakdown
* Title Conversion Efficiency

### 3. Attendance & Fan Engagement

* Attendance Growth
* Average Attendance Per Match
* Most Attended World Cups
* Tournament Expansion

### 4. Global Football Power Analysis

* FIFA Rankings Analysis
* Confederation Strength
* Global Football Power Balance

### 5. FIFA World Cup 2026 Prediction Engine

* Predicted Winners
* Top Contenders
* Confederation Strength
* World Map Visualization
* Monte Carlo Simulation Results

---

## Machine Learning Model

The prediction engine uses a **match level classifier** trained on 43,000+ historical international matches (2006–2023).

**Models trained and compared:**
- Logistic Regression (baseline)
- Random Forest Classifier
- HistGradientBoosting Classifier *(final model)*

**Evaluation:** 5-fold stratified cross-validation with F1 Macro scoring

**Simulation:** 10,000 Monte Carlo bracket runs simulating the complete WC 2026 tournament group stage through final match by match, using model-predicted win/draw/loss probabilities for every fixture.

**Explainability:** SHAP values show which features drive each team's predicted win probability.

---

## Key Outputs

* Historical World Cup Insights - https://public.tableau.com/app/profile/nellay.rawalh/viz/FIFA-WorldcupAnalysis/WorldCupDashboardFIFAAnalysis?publish=yes
* Team Top 4 Consistency Analysis - https://public.tableau.com/app/profile/nellay.rawalh/viz/FIFA-WorldcupAnalysis/FIFAWorldCupTop4ConsistencyAnalysis?publish=yes
* Attendance Trends - https://public.tableau.com/app/profile/nellay.rawalh/viz/FIFA-WorldcupAnalysis/WorldCupAttendanceFanEngagement?publish=yes
* Global Football Power Balance - https://public.tableau.com/app/profile/nellay.rawalh/viz/FIFA-WorldcupAnalysis/Dashboard-GlobalFootballPowerBalance?publish=yes
* 2026 World Cup Winner Probabilities - https://public.tableau.com/app/profile/nellay.rawalh/viz/FIFA-WorldcupAnalysis/DASHBOARD-FIFAWorldCup2026PredictionEngine?publish=yes

---

## Repository Structure

Data/
Notebooks/
assets/
Dashboards/
requirements.txt
README.md

---

## Author

Nellay Rawalh
Data Science Student
