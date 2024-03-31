# GIS Analysis for Vocational School Site Selection for the Disabled Community in Vietnam

## Project Overview
This GIS project focuses on identifying optimal locations for vocational schools tailored to the needs of the disabled community in Vietnam, particularly in the southern regions. Leveraging ArcGIS Pro's capabilities, we performed a detailed spatial analysis, incorporating factors such as land use, public transport accessibility, and population density, to pinpoint suitable school sites.

## Motivation
Addressing the educational disparity faced by people with disabilities (PWDs) in Vietnam, this project aims to enhance vocational training access. With a stark employment and education gap for PWDs, strategically placed vocational schools can significantly improve their livelihoods and integration into the workforce.

## Contents
- `report.pdf`: A detailed report on the project's objectives, methodology, analysis, and outcomes.
- `presentation.pptx`: A presentation summarizing the project's key points and findings.
- `crawl.ipynb`: A Python notebook for web scraping vocational school data from Vietnam's official site and augmenting it with location details via Google API.
- `vocational_data.xlsx`: The cleaned and final dataset for vocational schools.

In addition, the ArcGIS project with all the spatial analysis components can be accessed [here](https://drive.google.com/file/d/1Bf0yXdZCPW_tWaPTQT0IExfQWnxxgDxZ/view?usp=sharing).

## Data Processing and Analysis
Data sources range from publicly available datasets to custom-scraped vocational school data. The analysis workflow involve:

1. **Data Collection**: The data comes from a mix of public datasets and custom web scraping efforts, employing Python for data extraction from the official vocational schools website and leveraging Google API for precise geocoding.

2. **Data Cleaning**: Preparing data for analysis, including population density adjustments, land use categorization, and geocoding vocational schools.

3. **Spatial Analysis**: 
    - **Kernel Density and Hot Spot Analysis**: Identification of demographic and geographical patterns, utilizing ArcGIS's analytical tools to pinpoint areas with high concentrations of the target population.
    - **Weighted Overlay Analysis**: Integration of multiple factors such as land use, proximity to essential services, and accessibility to public transportation to assess potential school sites.
    - **Location Allocation Analysis**: Determining the most accessible and strategically located sites for the new schools.

4. **Result Interpretation**: Translating spatial data insights into concrete recommendations.

## Getting Started
To explore the project, download `arcgis_project.zip` from [here](https://drive.google.com/file/d/1Bf0yXdZCPW_tWaPTQT0IExfQWnxxgDxZ/view?usp=sharing), unzip and open the project in ArcGIS Pro. Review the `report.pdf` for a deep dive into the project's rationale, methodology, and findings. The `presentation.pptx` provides a concise overview, ideal for stakeholders. The `crawl.ipynb` notebook provides an in-depth look at the data collection process.

## Acknowledgments
This is a collaborative effort by Rachel Pham and Minh Tran.