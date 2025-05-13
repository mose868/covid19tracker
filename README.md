# COVID-19 Global Data Tracker

## Project Overview
The COVID-19 Global Data Tracker is a comprehensive Python-based data analysis tool designed to visualize and analyze global COVID-19 trends. This Jupyter notebook project pulls real-time data from trusted sources and provides insights through interactive visualizations.

## Features
- Real-time data collection from Johns Hopkins University COVID-19 repository
- Comprehensive analysis of case numbers, death rates, and vaccination progress
- Comparative analysis across multiple countries (Kenya, USA, India)
- Interactive visualizations including line charts, bar plots, and choropleth maps
- Detailed markdown insights and observations

## Requirements
The following Python libraries are required:
```
pandas
numpy
matplotlib
seaborn
plotly
```

## Installation
1. Ensure you have Python 3.6+ installed
2. Install required packages:
```
pip install pandas numpy matplotlib seaborn plotly
```
3. Launch Jupyter Lab:
```
python -m jupyter lab
```

## Usage
1. Open the `covid19tracker.ipynb` notebook in Jupyter Lab
2. Run each cell in sequence using Shift+Enter or the Run button
3. Explore the visualizations and analysis
4. Modify parameters or add new countries as needed

## Project Structure
- **Data Collection**: Fetches data from Johns Hopkins University GitHub repository
- **Data Cleaning**: Processes and prepares data for analysis
- **Exploratory Data Analysis**: Analyzes cases, deaths, and trends over time
- **Interactive Map**: Visualizes global data on an interactive world map
- **Insights**: Summarizes key findings and observations

## Data Sources
- [Johns Hopkins University COVID-19 Repository](https://github.com/CSSEGISandData/COVID-19)
- [Our World in Data COVID-19 Dataset](https://github.com/owid/covid-19-data)

## Example Output
The notebook generates various visualizations including:
- Cumulative COVID-19 cases over time
- Daily new cases (7-day moving average)
- Death rates by country
- Global choropleth maps

## Author
Moses Kimani

## License
MIT License

## Acknowledgments
- Johns Hopkins University for providing the COVID-19 data
- Our World in Data for vaccination statistics
