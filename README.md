# Energy Consumption Analysis Project

## Overview

This project is focused on analyzing global primary energy consumption data using Python. The dataset includes countries, regions, and continents with their energy consumption across several years. The analysis primarily focuses on identifying trends in energy consumption for individual countries.

## Project Structure

- **Dataset**: `primary-energy-cons.csv`  
  This file contains data on primary energy consumption (TWh) for various entities (countries, regions, continents) across several years.

- **Notebook**: `energy_consumption_analysis.ipynb`  
  This notebook contains all the code for loading, cleaning, analyzing, and visualizing the data.

## Installation and Setup

### Prerequisites
Before running the project, ensure you have the following installed:
- Python 3.x
- Jupyter Notebook or Jupyter Lab
- Required libraries: `pandas` & `matplotlib`

You can install the required libraries using the following command:

```bash
pip install pandas matplotlib notebook
```

### Running the Notebook
To run the notebook, use the following command to launch Jupyter:

```bash
jupyter notebook
```

Open the `energy_consumption_analysis.ipynb` notebook from the Jupyter interface.

## Dataset Description

- **Entity**: Name of the country, region, or continent.
- **Code**: ISO 3-letter country code.
- **Year**: The year of data collection.
- **Primary energy consumption (TWh)**: Energy consumption in terawatt-hours.

## Analysis

The analysis is carried out in a Jupyter Notebook and includes the following steps:

### Data Loading

The dataset is loaded using pandas for data analysis.

```python
import pandas as pd

df = pd.read_csv('primary-energy-cons.csv')
df.head()
```

### Visualizations

The notebook includes several visualizations using `matplotlib` to analyze and display trends in global energy consumption.

## Example Visualizations

- **Top Energy Consumers**: Bar plots showing the top energy-consuming countries.
- **Energy Consumption Trend**: Line plots for comparing trends across different countries.
  
## Conclusion

This project provides a comprehensive analysis of global energy consumption using Python and Jupyter Notebook. The notebook can be extended to include more complex analyses and visualizations, including predictive models.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- The dataset was obtained from [blob:https://ourworldindata.org/45aa90b8-7da0-4181-8920-2bb89fec0a9e].
- Libraries used: `pandas`, `matplotlib`, `Jupyter Notebook`.
