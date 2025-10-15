# 🌍 Global Fitness Trends Analysis

## 📘 Project Overview

This project analyzes **global and national interest in workouts** using **Google Trends data**.  
As a **Product Manager for a fitness studio**, the goal is to understand **how workout interests evolved globally**, identify **the most popular fitness trends during the COVID-19 pandemic**, and discover **potential markets for virtual home workouts**.

---

## 📊 Objectives

1. 🏋️ Identify when the global search for "workout" peaked.  
2. 📈 Determine the most popular fitness-related keyword:
   - During the **COVID-19 pandemic (2020–2021)**  
   - In the **current/latest recorded period**
3. 🌎 Compare workout interest among **United States**, **Australia**, and **Japan**.  
4. 🏠 Compare **home workout** interest between **Malaysia** and **Philippines** to guide market expansion.

---

## 📂 Dataset Description

All datasets are located in the `data/` folder.

| File | Description |
|------|--------------|
| **`workout.csv`** | Monthly global popularity index (0–100) for the keyword **"workout"**. |
| **`three_keywords.csv`** | Monthly global popularity indices for **"home workout"**, **"gym workout"**, and **"home gym"**. |
| **`workout_geo.csv`** | Average popularity of **"workout"** (2018–2023) by country. |
| **`three_keywords_geo.csv`** | Popularity (2018–2023) by country for **"home workout"**, **"gym workout"**, and **"home gym"**. |

---

## 🧠 Methodology

1. **Load and Clean Data**  
   Imported datasets using `pandas` and removed missing values.

2. **Global Peak Interest**  
   Identified the month and year where `'workout_worldwide'` reached its highest value.

3. **Keyword Popularity**  
   Determined the most popular keyword globally during:
   - The **COVID-19 period (2020–2021)**  
   - The **current/latest month**

4. **Geographical Comparison**  
   - Found the country with highest workout interest among *US, Australia, Japan*.  
   - Compared **home workout** interest between *Malaysia* and *Philippines*.

---

## 🧾 Variables and Outputs

| Variable | Description |
|-----------|--------------|
| `year_str` | Year when global search for "workout" peaked |
| `peak_covid` | Most popular keyword during COVID-19 |
| `current` | Most popular keyword currently |
| `top_country` | Country with highest interest (US, AUS, JP) |
| `home_workout_geo` | Country with higher interest in home workouts (Malaysia or Philippines) |

> The actual results depend on the dataset provided.

---

## ⚙️ Technologies Used

- **Python 3**
- **Pandas** → Data cleaning and analysis  
- **Matplotlib** → Data visualization  
- **Jupyter Notebook / VS Code** → Interactive analysis  

