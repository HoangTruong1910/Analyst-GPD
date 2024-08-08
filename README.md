# GDP Analysis of Countries

## Overview

This project aims to analyze the Gross Domestic Product (GDP) of various countries across different years. By examining this data, we aim to uncover trends in economic growth and provide insights into the economic performance of individual countries as well as comparative analysis among countries.

## Data Sources

- **Primary Data Source**: [World Bank GDP Data](https://data.worldbank.org/)
- **Datasets Used**:
  - `gdp_data.csv`: Contains GDP data of countries by year.
  - `countries_metadata.csv`: Includes additional metadata about the countries (e.g., population, area, geographical location).

## Project Structure

- **Data Cleaning**: Preprocessing steps including handling missing values, normalizing country names, and preparing the data for analysis.
- **Analysis**:
  - Calculate average GDP, GDP per capita, and GDP growth rates.
  - Compare GDP across regions and groups of similar countries.
  - Identify GDP growth trends over time.
- **Visualization**:
  - Trend lines for GDP over the years.
  - Comparative bar charts for GDP among countries.
  - World map visualization showing GDP by region.

## Technologies Used

- **Programming Language**: Python
- **Libraries**:
  - `pandas`: For data manipulation and analysis.
  - `matplotlib` & `seaborn`: For data visualization.
  - `geopandas`: For mapping GDP data on a world map.

## Installation

1. **Clone the repository**:
   '''bash
   git clone https://github.com/HoangTruong1910/Analyst-GPD.git
   cd Analyst-GPD'''

2. Install required libraries:
   '''bash
pip install -r requirements.txt'''

3. Run the analysis:

'''bash
python analyze_gdp.py'''

## Results
* Analysis Report: The report.pdf file contains the analysis results and visualizations.
* GDP Map: The gdp_map.png file provides a world map view of GDP distribution among countries.

## Contributing
We welcome contributions to improve this project! If you find any issues or have suggestions for new features, please open an issue or submit a pull request.

## License
This project is licensed under the MIT License.
