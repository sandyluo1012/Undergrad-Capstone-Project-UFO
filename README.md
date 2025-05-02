# 🛸 Close Encounters of the Unidentified Kind
**Stats 140XP Final Project – Winter 2023**  
**UCLA Statistics Department**

## 👥 Team Members
Brandon Hao, Dylan McCann, Rene Delgadillo, Keying Zhang, Yijiao Guo, Wenqian Luo

## 📌 Project Overview
This project investigates patterns in reported UFO sightings across North America, using a dataset collected by the National UFO Reporting Center (NUFORC). Spanning over 170,000 reports from 1969 to 2019, our analysis aims to uncover relationships between sighting frequency and geographic, temporal, and seasonal factors.

Our central questions include:
- Does geographic location (particularly proximity to military bases) influence sighting frequency?
- Has the number of sightings changed over time, and are these changes tied to societal or technological trends?
- How do seasonal patterns affect the likelihood of sightings?

## 🔍 Data Source
- **National UFO Reporting Center (NUFORC)**  
  Website: http://www.nuforc.org  
  Format: Cleaned and analyzed CSV data  
  Time range: 1969–2019  
  Fields include: `location`, `date`, `time`, `duration`, `description`, `latitude`, `longitude`, `shape`

## 🧪 Methodology
### 1. Exploratory Data Analysis
- Removed entries with missing or corrupted data
- Standardized state, city, and coordinate entries
- Time-based aggregation: sightings per year, month, and hour

### 2. Hypotheses and Visualizations
- **Geographic Analysis**: Created heatmaps of sightings overlaid with military base locations
- **Temporal Trends**: Plotted sightings per year to observe sudden increases (e.g., post-2006 spike)
- **Seasonal Patterns**: Interaction plots by year and season

## 📊 Key Findings

### 📍 Geographical Correlation
- High frequency of sightings in coastal and urban regions
- Moderate positive correlation with areas that have military bases, though not consistent nationwide

### 📈 Temporal Trends
- Significant spike in sightings around 2006–2007
- Post-2006: greater year-to-year variability in reported sightings
- Hypothesis: Smartphone adoption (e.g., iPhone in 2007) may contribute to reporting frequency

### 🍂 Seasonal Variation
- Historically, summer had the highest proportion of sightings
- Post-2006: seasonal effects diminished, possibly due to increased year-round reporting


## 📚 References
- Blundell, R. (2018). *USOs and UFOs: Underwater mysteries and sightings.*
- NUFORC. *North American UFO sightings database.* http://www.nuforc.org/
- Pilkington, M. (2017). *Exploring the rise of smartphone-based reporting of UFO sightings.*

## 🔚 Conclusion
This project demonstrates how statistical analysis can provide insight into mysterious social phenomena like UFO sightings. Our findings suggest that human activity, technology adoption, and perhaps even cultural awareness play a large role in how and when such events are reported.

Further work could include:
- Regression modeling of sighting probability based on population and distance to military bases
- Hypothesis testing (e.g., ANOVA, Tukey HSD) for seasonal differences
- Deep learning on textual descriptions to classify types of sightings

---

> _Stats 140XP: Practice of Statistical Consulting | UCLA | Winter 2023_
