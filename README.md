# Dashboard-Project
This repository contains a dynamic, interactive COVID-19 dashboard built using Dash and Plotly. The dashboard visualizes global COVID-19 data trends, providing insights through interactive charts, maps, and graphs. It offers features like time-series animations, region-wise breakdowns, and country-specific visualizations.

# COVID-19 Dashboard

## Overview
This repository contains an interactive COVID-19 dashboard built using Dash and Plotly. The dashboard visualizes the global spread and trends of COVID-19 using data-driven charts and graphs. It provides insightful visualizations such as an animated map, pie charts, and country-specific trends to help users better understand the pandemic's progression.

## Features
- **Animated Geo Map**: Time-series animation showing the global spread of COVID-19 cases.
- **Pie Chart**: Displays the percentage distribution of cases by continent.
- **Sunburst Chart**: Hierarchical visualization of cases by continent and country.
- **Country-Specific Analysis**: Select a country to view its metrics (total cases, deaths, recoveries, active cases) and trends over time.
- **Interactive UI**: Dropdown menus and hover features for a seamless experience.

## Technologies Used
- **Dash**: Web application framework for Python.
- **Plotly**: Library for interactive data visualization.
- **Pandas**: Data manipulation and analysis.
- **Python**: Backend scripting language.

## Prerequisites
- Python 3.7 or higher.
- Required Python libraries:
  ```bash
  pip install dash plotly pandas
  ```

## Data Sources
1. **cleaned_covid_data1.csv**: Contains preprocessed COVID-19 data.
2. **worldometer_data1.csv**: Provides global and continental COVID-19 statistics.
3. **covid_19_clean_complete1.csv**: Includes daily case data with country-level details.

## How to Run the Dashboard
1. Clone the repository:
   ```bash
   git clone [your-repository-url]
   cd [your-repository-folder]
   ```
2. Place the provided datasets in the project folder or update file paths in `app.py`.
3. Run the application:
   ```bash
   python app.py
   ```
4. Open your web browser and navigate to `http://127.0.0.1:8050` to view the dashboard.

## Project Structure
```
.
├── app.py                  # Main application script
├── cleaned_covid_data1.csv # Dataset 1
├── worldometer_data1.csv   # Dataset 2
├── covid_19_clean_complete1.csv # Dataset 3
├── README.md               # Documentation
```

## Screenshots
[Add screenshots of the dashboard here to give users a preview of its features.]

## Future Enhancements
- Real-time data integration for live updates.
- Additional filters for regional and demographic analysis.
- More detailed metrics and visualizations.


## Acknowledgments
- Libraries and frameworks: Dash, Plotly, Pandas.

---

Feel free to contribute to the project by opening issues or submitting pull requests!

