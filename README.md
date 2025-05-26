# Elevate_Labs_Task_1
# 🐿️ Central Park Squirrel Census Analysis

This project analyzes the 2018 Central Park Squirrel Census dataset using Python and visualizes different attributes of squirrels observed in Central Park, NYC. It utilizes libraries like `pandas`, `seaborn`, and `matplotlib` for data handling and visualization.

## 📁 Dataset

The dataset used is:  
**2018_Central_Park_Squirrel_Census_-_Squirrel_Data_20250526.csv**

This dataset contains information about individual squirrel sightings in Central Park, including location, fur color, behavior, and other attributes.

## 🔧 Features

The script performs the following actions:

- Loads and previews the squirrel dataset.
- Checks for uniqueness of the Squirrel IDs.
- Sets `Unique Squirrel ID` as the DataFrame index.
- Displays data dimensions, types, and basic statistics.
- Checks for missing and duplicate values.
- Adds a new column called `Family` by summing `X` and `Y` coordinates.
- Visualizes:
  - Primary fur colors by Family.
  - Distribution of Primary Fur Colors using histogram.
- Extracts the number of Gray, Cinnamon, and Black squirrels.
- Saves the fur color summary into a new CSV file (`squirrel_data.csv`).

## 📊 Visualizations

- **Countplot** of Primary Fur Color across different families.
- **Histogram** showing the distribution of fur colors among squirrels.

## 🐍 Dependencies

Make sure you have the following Python libraries installed:

```bash
pip install pandas seaborn matplotlib
