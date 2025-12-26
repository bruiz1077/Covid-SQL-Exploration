# Covid-SQL-Exploration
Advanced SQL exploration of global COVID‑19 data using joins, CTEs, window functions, and rolling metrics.

# COVID‑19 SQL Data Exploration

This project explores global COVID‑19 data using advanced SQL techniques to analyze cases, deaths, infection rates, and vaccination progress across countries and continents. The goal is to transform raw data into meaningful insights using clean, well‑structured SQL queries.

---

## 📊 Project Overview

Using the **Our World in Data COVID‑19 dataset**, this analysis answers key questions such as:

- How did COVID‑19 spread across different countries?
- What percentage of each population was infected?
- Which countries and continents experienced the highest death counts?
- How did vaccination progress over time?
- What rolling trends can we observe in new vaccinations?

The project demonstrates strong SQL fundamentals and analytical thinking.

---

## 🛠️ Skills Demonstrated

- Joins  
- Common Table Expressions (CTEs)  
- Window Functions  
- Aggregate Functions  
- Data Type Conversion  
- Creating Views  
- Rolling Calculations  
- Data Cleaning & Exploration  

---

## 🗂️ Dataset

The project uses two datasets:

- **CovidDeaths**  
- **CovidVaccinations**

Both come from the *Our World in Data* COVID‑19 repository.

---

## 🔍 Key Analyses Performed

### 1. Exploring raw COVID‑19 case and death data  
Selecting location, date, total cases, total deaths, and population.

### 2. Calculating death percentage  
Shows the likelihood of dying if infected.

### 3. Infection rate vs. population  
Determines what percentage of each population contracted COVID‑19.

### 4. Countries with highest infection rates  
Using `MAX()` and population‑based calculations.

### 5. Countries & continents with highest death counts  
Using `CAST()` to clean numeric fields.

### 6. Global totals  
Summing new cases and new deaths to calculate global death percentage.

### 7. Vaccination progress  
Joining deaths and vaccination tables to calculate rolling totals of people vaccinated.

### 8. CTE and Temp Table versions  
Reusable logic for calculating percent vaccinated.

### 9. Creating a SQL View  
Stores rolling vaccination metrics for BI dashboards.

---

## 📁 Project Structure
covid-sql-exploration/
│── sql/
│     └── covid_exploration.sql
│── README.md

