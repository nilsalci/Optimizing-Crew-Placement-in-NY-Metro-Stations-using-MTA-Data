# Optimizing Crew Placement in NY Metro Stations using MTA Subway Data

## Project Description

This project leverages NYC subway data (2020-2024) to optimize the deployment of street teams for cancer awareness campaigns. By analyzing passenger densities, demographic trends, and public health statistics, it identifies high-impact locations and times for awareness activities. The analysis integrates multi-year subway ridership data with health insights to improve targeted outreach strategies.

## Data Sources

- **MTA Subway Hourly Ridership**: Covers hourly subway data from July 2020 onward ([Data Source](https://data.ny.gov/Transportation/MTA-Subway-Hourly-Ridership-Beginning-July-2020/wujg-7c2s/about_data)
- **NYC Health Cancer Statistics**: Provides cancer incidence by borough, age, and gender ([Health Data](https://www.health.ny.gov/statistics/cancer/registry/atGlance.htm)).
- **NYC Population Statistics**: Insights into borough demographics ([Population Data](https://www.fox5ny.com/news/nyc-population-2024)).

## Technologies and Tools

- **Programming Languages**: Python
- **Libraries**: Pandas, NumPy, Matplotlib
- **Visualization Tools**: Bar and line charts for trend analysis

## Analysis Steps

1. **Data Cleaning**: Removed irrelevant columns and focused on the most recent year's data.
2. **Categorization**: Grouped data by borough, station, and time intervals.
3. **Visualization**: Created visual aids to explore ridership trends by time and location.
4. **Cross-Analysis**: Combined ridership and cancer incidence data to identify optimal deployment strategies.

## Key Findings

- **Borough Insights**: Manhattan has the highest ridership density, followed by Brooklyn, Queens, and the Bronx.
- **Station Analysis**: Times Square-42 St, Grand Central-42 St, and 34th Penn Station are the busiest.
- **Temporal Trends**:
  - Peak ridership months: March, April, May.
  - Busiest days: Wednesdays.
  - Rush hours: 7-9 AM and 4-6 PM.
- **Health Data Correlation**: Cancer cases are highest in Manhattan and more common among men aged 40-75.

## Recommendations

- Deploy teams during peak ridership hours (7-9 AM, 4-6 PM) on Wednesdays in high-traffic stations.
- Prioritize boroughs with high cancer rates and dense station networks, such as Manhattan and Brooklyn.
- Focus on months with higher ridership and favorable weather for campaigns (March-May).

## How to Run the Project

### Prerequisites

- Python 3.7+
- Required libraries: Pandas, NumPy, Matplotlib

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/nilsalci/Optimizing-Crew-Placement-in-NY-Metro-Stations-using-MTA-Data
   ```
2. Run the Jupyter Notebook:
   ```bash
   jupyter notebook Optimizing-Crew-Placement-with-MTA-Data.ipynb
   ```

## Results and Visuals

- Ridership density maps by borough and station.
- Monthly, daily, and hourly trends for subway use.
- Cross-referenced charts combining health and ridership data.

## Contributors

- [@Sevag9](https://github.com/Sevag9)
- [@nilsalci](https://github.com/nilsalci)

## References

- [MTA Subway Hourly Ridership Data](https://data.ny.gov/Transportation/MTA-Subway-Hourly-Ridership-Beginning-July-2020/wujg-7c2s/about_data)
- [NYC Health Cancer Statistics](https://www.health.ny.gov/statistics/cancer/registry/atGlance.htm)
- [NYC Population Statistics](https://www.fox5ny.com/news/nyc-population-2024)

---

This project was developed by Sevag Altıntopuz and Nilsu Salıcı as part of an analytical initiative for the Cancer Awareness Foundation. Feedback and contributions are welcome!

