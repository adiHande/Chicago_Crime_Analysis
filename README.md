# Chicago Crime Analysis

A data analysis project exploring Chicago crime data using Python, Pandas, Matplotlib, and Seaborn. The notebook examines crime types, districts, dates and times, arrests, domestic incidents, and other patterns in the dataset through summary statistics and visualizations.

## Analysis Includes

* Data cleaning and missing-value handling
* Date and time feature extraction
* Most common crime types and districts
* Crime trends by month, day of week, and hour
* Arrest vs. non-arrest comparisons
* Domestic vs. non-domestic crime comparisons
* Crime distribution visualizations

## Run the Notebook

The notebook is designed to run in **Google Colab**.

[Open in Google Colab](https://colab.research.google.com/drive/1VDiloWw3aikwBc3VzJvi7LI5SV1iYXW5)

1. Make sure the dataset is downloaded to your computer and named exactly:
```text
chicago_crime.csv
```
2. Open the notebook using the link above.
3. Run the cells from top to bottom.
4. When prompted, upload the Chicago crime dataset.
5. Continue running the remaining cells to perform the analysis and generate the visualizations.

The notebook loads the dataset with:

```python
df = pd.read_csv("chicago_crime.csv")
```

so the uploaded CSV must use that filename unless the path in the notebook is changed.

## Requirements

Google Colab includes the required Python libraries by default:

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn

No additional package installation is required.

## Stack & Concepts

Python, Pandas, NumPy, Matplotlib, Seaborn, Data Cleaning, Data Exploration, Data Visualization
