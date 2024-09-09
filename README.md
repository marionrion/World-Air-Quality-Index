# Global Air Quality Index: Analyzing Pollution Patterns Across the World

![image](https://github.com/user-attachments/assets/de2eab60-dfd0-4d69-8c12-34283a59394c)
🌍

This project involves analyzing air quality data from cities around the world to understand pollution patterns and assess the impact of various pollutants. The dataset provides a snapshot of air quality measurements, enabling us to explore how different pollutants affect overall air quality and identify areas with significant pollution concerns.

## Data Summary

The data includes air quality measurements from cities across the globe. It captures multiple pollutants and their corresponding Air Quality Index (AQI) values. The dataset allows us to assess the severity of air pollution, understand the contribution of individual pollutants, and visualize pollution trends across different regions.

### Dataset Fields
- **Country**: The country where the city is located.
- **City**: The city in which the air quality was measured.
- **AQI Value**: The overall Air Quality Index value representing the air quality level.
- **AQI Category**: Categorical label classifying the AQI value (e.g., 'Good', 'Moderate', 'Unhealthy').
- **CO AQI Value**: Air Quality Index value for Carbon Monoxide (CO) concentration.
- **CO AQI Category**: Categorical label classifying the AQI for CO.
- **Ozone AQI Value**: Air Quality Index value for Ozone concentration.
- **Ozone AQI Category**: Categorical label classifying the AQI for Ozone.
- **NO2 AQI Value**: Air Quality Index value for Nitrogen Dioxide (NO2) concentration.
- **NO2 AQI Category**: Categorical label classifying the AQI for NO2.
- **PM2.5 AQI Value**: Air Quality Index value for Particulate Matter (PM2.5) concentration.
- **PM2.5 AQI Category**: Categorical label classifying the AQI for PM2.5.
- **lat**: Latitude of the city, useful for geospatial analysis.
- **lng**: Longitude of the city, useful for geospatial analysis.

## Getting Started

To explore the analysis, you can run the provided Jupyter Notebooks:

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Open the Jupyter Notebooks using Jupyter Notebook or JupyterLab.

### Prerequisites

Ensure you have the following packages installed to run the notebooks:

- pandas
- matplotlib
- seaborn
- numpy

You can install the required packages using:

```bash
pip install pandas matplotlib seaborn numpy
```

## Data Analysis

### Understanding Global Air Quality

The analysis explores air quality levels and pollutant contributions across various cities globally. By examining AQI values and pollutant-specific data, we can identify pollution hotspots and trends, providing valuable insights into regional air quality variations.

### Key Findings

- **Overall Air Quality**: Most cities fall within the "Good" to "Moderate" AQI categories, indicating relatively acceptable air quality. However, higher AQI values in some regions highlight areas with poorer air quality.
- **Pollutant Contributions**: PM2.5, NO2, CO, and Ozone are significant contributors to air pollution. The data shows varying correlations between these pollutants, suggesting potential shared sources or interactions.
- **Geospatial Insights**: Geographic visualization reveals clusters of high pollution levels, particularly in regions with significant industrial or vehicular emissions.

### Additional Key Observations

- **Regional Patterns**: Areas in Africa, South America, and South Asia exhibit moderate AQI levels, while parts of the U.S., Europe, and China show a mix of good and moderate air quality. Southeast Asia has notable clusters of unhealthy air quality.
- **Trends Over Time**: The analysis highlights trends in pollution levels, helping identify regions that are improving or deteriorating in terms of air quality.

## Conclusion

The data analysis underscores the importance of monitoring air quality to protect public health and environmental sustainability. By identifying pollution hotspots and understanding the contributions of various pollutants, we can better inform policies and interventions aimed at improving air quality globally.
