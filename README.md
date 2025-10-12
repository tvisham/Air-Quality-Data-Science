
# Air Quality Data Science Project: NYC Analysis

## Project Overview
This project provides a comprehensive analysis of air quality trends in New York City, leveraging publicly available datasets. The primary focus is on understanding pollutant patterns, their health impacts, and the influence of major events such as the 2023 Canadian wildfires.

## Significance
Air pollution is a critical public health concern, especially in urban environments. By analyzing historical and recent air quality data, this project:
- Identifies spatial and temporal trends in key pollutants (PM2.5, NO2, Ozone, SO2, etc.)
- Assesses the impact of external events (e.g., wildfires) on NYC air quality
- Highlights correlations between pollution sources (traffic, boilers, air toxics) and health outcomes
- Provides actionable insights for policymakers, researchers, and the public

## Dataset Sources
- [NYC Air Quality Data](https://catalog.data.gov/dataset/air-quality)
- [NYC Planning Datasets](https://www.nyc.gov/content/planning/pages/resources#datasets)

## Tech Stack
**Python** is used for all data analysis and visualization due to its rich ecosystem:
- **pandas**: Data manipulation and cleaning
- **matplotlib & seaborn**: Visualization of trends and correlations
- **geopandas**: Geospatial analysis and mapping of pollutant concentrations

These libraries are chosen for their reliability, flexibility, and strong support for scientific computing and data visualization.

## Key Results & Outputs
- **Temporal Analysis**: Plots showing trends of PM2.5, NO2, Ozone, SO2 over time
- **Spatial Analysis**: Maps visualizing pollutant concentrations across NYC boroughs
- **Correlation Analysis**: Heatmaps and bar charts revealing relationships between pollution sources and health metrics
- **Impact Assessment**: Quantitative evaluation of the 2023 Canadian wildfires on NYC air quality

### Example Output Files
- `PM25_vs_Time.png`, `NO2_vs_Time.png`, `Ozone_vs_Time.png`, `SO2_vs_Time.png`: Time series plots
- `nyc_most_recent_pm25_pollutant_map.png`, etc.: Geospatial pollutant maps
- `pm25_correlation_heatmap_with_nox_so2.png`: Correlation heatmap

## Installation & Usage
To run this analysis locally:

1. **Clone the repository**
	```powershell
	git clone https://github.com/tvisham/Air-Quality-Data-Science.git
	cd Air-Quality-Data-Science
	```

2. **Install Python dependencies**
	```powershell
	pip install pandas matplotlib seaborn geopandas
	```

3. **Download required datasets**
	- Place CSV and shapefile data in the appropriate paths as referenced in the notebook.

4. **Run the Jupyter Notebook**
	```powershell
	jupyter notebook "FBLA Air Quality.ipynb"
	```
## Contact & Contributions
For questions, suggestions, or contributions, please open an issue or submit a pull request.

