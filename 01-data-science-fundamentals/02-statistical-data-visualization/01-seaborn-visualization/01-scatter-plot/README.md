## Scatter Plot using Seaborn

The Scatter Plot is a visualization technique used to display the relationship between two continuous variables. It represents each data point as a marker on a two-dimensional plane, with the x-axis representing one variable and the y-axis representing another variable.

Seaborn is a popular Python library for data visualization, and it provides a convenient way to create Scatter Plots with various customization options.

### Table of Contends
- [Installation](#installation)
- [Usage](#usage)
- [Customization Options](#customizationoptions)
    - [Data and Variables](#dataandvariables)
    - [Grouping Variables](#groupingvariables)
    - [Appearance Options](#appearanceoptions)
    - [Legend Options](#legendoptions)
- [Examples](#examples)
- [Conclusion](#conclusion)

### Installation

To use the Scatter Plot functionality in Seaborn, you need to have Seaborn installed. If you haven't installed it yet, you can do so using pip:

```python
pip install seaborn
```

### Usage

To create a Scatter Plot using Seaborn, you can use the scatterplot() function. Here is a basic example:

```python
import seaborn as sns
import matplotlib.pyplot as plt

# Create sample data
x = [1, 2, 3, 4, 5]
y = [5, 4, 3, 2, 1]

# Create Scatter Plot
sns.scatterplot(x=x, y=y)

# Display the plot
plt.show()
```
This will create a Scatter Plot with the x-values on the x-axis and the y-values on the y-axis.

### Customization Options

Seaborn provides several options to customize the Scatter Plot. Here are some of the available options:

### Data and Variables
- `x` and `y`: The variables used for the x-axis and y-axis of the Scatter Plot.
- `data`: The DataFrame or array-like object containing the data.

### Grouping Variables
- `hue`: Grouping variable that will produce points with different colors.
- `style`: Grouping variable that will produce points with different markers or line styles.
- `size`: Grouping variable that will produce points with different sizes.

### Appearance Options
- `palette`: The color palette to use for mapping the hue variable.
- `markers`: List of markers to use for each level of the style variable.
- `linewidths`: Width of the marker edges.
- `edgecolors`: Color of the marker edges.
- `alpha`: Transparency of the markers.

### Legend Options
- `legend`: Whether to show a legend (True/False) or specify its location.
- `legend_title`: Title of the legend.
- `legend_title_fontsize`: Font size of the legend title.
- `legend_title_alignment`: Alignment of the legend title.
- `legend_title_rotation`: Rotation of the legend title.
- `legend_bbox`: Bounding box properties of the legend title.
- `legend_label_fontsize`: Font size of the legend labels.
- `legend_handle_size`: Size of the legend handles.
- `legend_handle_alpha`: Transparency of the legend handles.
- `legend_handle_edgecolor`: Edge color of the legend handles.
- `legend_handle_linewidth`: Width of the legend handle edges.
- `legend_handle_linestyle`: Line style of the legend handles.
- `legend_handle_marker`: Marker style of the legend handles.
- `legend_handle_markeredgecolor`: Edge color of the legend handle markers.
- `legend_handle_markerfacecolor`: Face color of the legend handle markers.
- `legend_handle_markeredgewidth`: Edge width of the legend handle markers.
- `legend_handle_markerpath`: Custom path of the legend handle markers.

These options allow you to customize various aspects of the Scatter Plot, including the appearance of markers, legends, colors, sizes, and styles based on different variables.

### Examples
To see more examples of Scatter Plots with different customization options using Seaborn, please refer to the [Scatter Plot Examples Notebook](https://github.com/rvigneshwaran/datascience-implementations/blob/main/01-data-science-fundamentals/02-statistical-data-visualization/01-seaborn-visualization/01-scatter-plot/01-scatter-plots-demonstration.ipynb).

### Conclusion
The Scatter Plot is a powerful visualization tool provided by Seaborn that allows you to explore relationships between two continuous variables in your data. With Seaborn's customization options, you can create visually appealing Scatter Plots tailored to your specific needs.

For more information on using Seaborn and its Scatter Plot functionality, please refer to the [Seaborn documentation](https://seaborn.pydata.org/).

Enjoy exploring and visualizing your data with Scatter Plots in Seaborn!
