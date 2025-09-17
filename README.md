## 🌍 Global Pesticide Use vs. Postharvest Food Loss (1990–2023)

## 📂 Data Sources
- FAO – Inputs Pesticide Use Database (1990- 2023)  
- UNSD – Methodology (country/region mapping)  
- Our World in Data – postharvest loss (2016, 2020, 2021) 

## 🎯 Goal / Objective
This project examines the relationship between global pesticide use (1990–2023) and postharvest food losses (2016, 2020, 2021). The analysis explores:
-- Whether more pesticide use actually reduces postharvest losses
-- How trends differ by region, crop type, and over time
-- The impact of major events (like COVID-19) on pesticide use and food preservation

## 🛠️ Major Workflow and Findings 

--- Removed empty values and zeros
--- Standardized country/region names and merged datasets with UN mapping to combine postharvest loss data with the pesticide uses data
--- Calculated global pesticide use over three decades (1990–2023)
--- Found almost steady growth from 1990 to 2023
--- Identified the Top 8 sub-regions by pesticide use: Latin America & Caribbean, Northern America, Eastern Asia, South-eastern Asia, Western Europe, Southern Europe, Eastern Europe, Southern Asia
--- Built stacked bar charts (1990, 2000, 2010, 2015, 2020, 2023) to show shifts in herbicides, insecticides, fungicides, etc., over time
--- Found that postharvest losses are largely independent of pesticide use (based on data from the years 2016, 2020, and 2021).
--- Even with very high pesticide usage, postharvest losses remain significant in some regions.
--- Efficiency Ratios (Food loss per unit pesticide, lower = better)
      o	Northern Europe: Most efficient (~5.75) (low loss per pesticide unit).
      o	Central & Western Asia: Moderate (~12–13)
      o	Southern Asia, Latin America, East/Southeast Asia: Inefficient (>100)
      o	North America: Least efficient (~403.5), very high pesticide use with little preservation benefit.
--- During COVID-19, pesticide use shifted slightly, but food loss rose, showing reduced efficiency under pandemic conditions.

## 📊 Results / Insights 
--- Key Insight 1: Pesticide use has grown globally, but does not strongly reduce postharvest losses.
--- Key Insight 2: Food loss (~10–11%) remains relatively stable despite changing pesticide use.
--- Key Insight 3: Efficiency depends more on regional infrastructure, storage, and supply chain capacity than on chemical input levels.
--- Key Insight 4: Europe demonstrates low loss with moderate inputs, while Asia and North America reveal inefficiencies. ((Asia’s trends may also reflect cultural and consumption patterns)
--- Key Insight 5: A global “efficiency paradox” exists — more pesticides do not automatically mean less food waste.

## 🚀 Future Work
--- Implementing Machine Learning
