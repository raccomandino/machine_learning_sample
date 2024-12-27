# Machine Learning Data Visualization Sample Evaluation

This repository showcases various approaches to visualizing machine learning data using Python. It includes examples of scatter plots, bar charts, pie charts, histograms, and advanced techniques like sunburst charts and radar plots. These visualizations help understand patterns, trends, and insights in datasets. I will further update the last version on my Kaggle account.

## Features

- **Data Preparation:** Includes code for loading, cleaning, and transforming datasets.
- **Visualization Libraries:** Demonstrates the use of popular Python libraries:
  - Pandas
  - Seaborn
  - Matplotlib
  - Plotly
- **Charts and Plots:**
  - Scatter Plots
  - Box Plots
  - Histograms
  - Sunburst Charts
  - Pie Charts
  - Heatmaps
- **Interactive Features:** Integration of Plotly for dynamic and interactive visualizations.

## Datasets

- Heart Disease Dataset
- Gapminder Dataset
- Job Market Dataset (Malaysia)

## Code Examples

### Scatter Plot

```python
import plotly.express as px

fig = px.scatter(
    df,
    x="chol",
    y="age",
    color="cp",
    size="oldpeak",
    hover_name="exang"
)
fig.update_layout(title_text="Cholesterol vs Age (colored by Chest Pain)")
fig.show()
```

### Bar Chart

```python
fig = px.bar(
    df,
    x="age",
    y="chol",
    color="sex",
    height=400
)
fig.show()
```

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/raccomandino/machine_learning_sample.git
   cd machine_learning_sample
   ```
2. Install the required libraries:
   ```bash
   pip install pandas numpy seaborn matplotlib plotly
   ```
3. Run the Jupyter Notebook or Python scripts:
   ```bash
   jupyter notebook
   ```

## Resources

- [Part 1: Python for Machine Learning Visualization](https://www.kaggle.com/code/pythonafroz/python-for-machine-learning-visualization-part-01)
- [Part 2: Advanced Visualizations](https://www.kaggle.com/code/pythonafroz/python-for-machine-learning-visualization-part-03)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
