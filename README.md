# LEGO Data Analysis and Visualization

## Project Overview

This project analyzes LEGO dataset to explore trends and characteristics of LEGO sets over time. Using Python and Google Colab, 
the analysis combines data from `sets.csv` and `themes.csv` to visualize key metrics such as the average number of parts per LEGO set, 
the number of sets released each year, and the popularity of different LEGO themes.

## Features

- **Data Integration:** Merges data from LEGO sets and themes to analyze relationships and trends.
- **Exploration and Transformation:** Calculates metrics like average number of parts and number of sets per theme.
- **Visualization:** Creates bar charts and line plots to visualize top LEGO themes and trends in set complexity over time.
- **Insights:** Provides a deeper understanding of LEGO's product offerings and their evolution.

## Files

- `sets.csv`: Contains information about LEGO sets, including year of release and number of parts.
- `themes.csv`: Contains information about LEGO themes, including theme names and IDs.
- `analysis.py`: Python script performing data analysis and visualization.

## Getting Started

### Prerequisites

Ensure you have the following Python packages installed:
- pandas
- matplotlib

You can install the required packages using pip:

```bash
pip install pandas matplotlib
```

### Setup

1. **Clone the Repository:**


2. **Prepare the Data:**

   Place your `sets.csv` and `themes.csv` files in the `data/` directory.

3. **Run the Analysis:**

   Execute the Python script to perform data analysis and generate visualizations:

   ```bash
   python analysis.py
   ```

   Alternatively, you can run the analysis directly on Google Colab by uploading your `sets.csv` and `themes.csv` files to the Colab environment.

## Usage

- **Data Integration:**
  Merges `sets.csv` and `themes.csv` to link theme information with the number of sets.

- **Visualization:**
  - Bar charts to show the top LEGO themes by the number of sets.
  - Line plots and scatter plots to visualize trends over time.


## Using Google Colab

To run the analysis on Google Colab:

1. Open Google Colab and create a new notebook.
2. Upload your `sets.csv` and `themes.csv` files to the notebook.
3. Copy and paste the code from `analysis.py` into a cell in the Colab notebook.
4. Execute the cells to perform the analysis and visualize the results.

