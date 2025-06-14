# Global PM10 Air Quality Analysis (2010-2022)

## 1. Overview

This project conducts a comprehensive spatio-temporal and statistical analysis of global Particulate Matter (PM10) concentrations from 2010 to 2022. Utilizing the World Health Organization (WHO) Air Quality Database, the analysis aims to visualize global air quality trends, identify significant pollution hotspots and coldspots, and quantify temporal changes across different continents. The insights derived are crucial for understanding global air pollution patterns and informing environmental policy and public health strategies.

## 2. Features & Analysis Performed

- **Spatio-Temporal Visualization:** Dynamic animated maps illustrating yearly changes in global PM10 concentrations from 2010 to 2022.
- **Global Spatial Pattern Analysis (Hotspot & Coldspot Detection):** Application of Getis-Ord Gi\* statistics to identify statistically significant clusters of high (hotspots) and low (coldspots) PM10 concentrations.
- **Cross-Regional Comparative Trend Analysis:** Visual comparison of average PM10 concentration trends across major continents.
- **Quantifying Temporal Trends:** Statistical analysis using linear regression to determine the rate and significance of PM10 changes for each continent.

## 3. Data Sources

- **PM10 Concentration Data:** World Health Organization (WHO) Air Quality Database.
- **Global Administrative Boundaries:** Natural Earth data.

## 4. Methodology & Tools

The analysis is conducted primarily in Python, leveraging a suite of specialized libraries:

- **Pandas:** For robust data manipulation and cleaning.
- **GeoPandas:** For handling geospatial data, including shapefiles and spatial operations.
- **PySAL (Python Spatial Analysis Library):** Specifically `libpysal` for spatial weights matrix creation (K-Nearest Neighbors) and `esda` for hotspot analysis (Getis-Ord Gi\*).
- **Matplotlib:** For creating static and dynamic visualizations.
- **Imageio:** For compiling individual map frames into animated GIFs.
- **Scipy.stats:** For statistical trend analysis (linear regression).

## 5. Key Results Summary

- **Global Trends:** While overall global PM10 levels show signs of improvement, significant regional disparities persist.
- **Hotspots:** Persistent and prominent PM10 hotspots were identified across East Asia, parts of the Middle East, and Eastern Europe.
- **Coldspots & Improvement:** North America and Oceania consistently exhibited low PM10 concentrations and showed statistically significant decreasing trends.
- **Asia's Challenge:** Despite a visually apparent decline, PM10 trends in Asia were not statistically significant in a linear model, indicating high variability and ongoing challenges in air quality management.

## 6. How to Run the Analysis

To replicate and explore this analysis, follow these steps:

### Prerequisites

- Python 3.8+
- Jupyter Notebook (or Jupyter Lab)

### Setup

1.  **Clone the Repository:**

    ```bash
    git clone https://github.com/tobijay666/InvisibleBreath.git
    cd InvisibleBreath
    ```

2.  **Create a Virtual Environment (Recommended):**

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: `venv\Scripts\activate`
    ```

3.  **Install Dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
