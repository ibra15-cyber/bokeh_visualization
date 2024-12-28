# Bokeh Visualization Examples

This repository contains a series of examples demonstrating the use of Bokeh, a Python library for interactive and web-ready visualizations. The examples illustrate various plotting techniques, including time series visualization, stacked bar plots, and hexbin plots. 

## Features

- **Time Series Plot**: Visualize stock prices over time using data from a CSV file.
- **Stacked Bar Chart**: Represent categorical data across multiple years in a stacked bar format.
- **Hexbin Plot**: Efficiently visualize a large number of data points using hexagonal binning.
- **Simple Line Plot**: Generate a line plot using data from a CSV file.

## Installation

To run the examples, ensure you have the required Python libraries installed:

```bash
pip install bokeh pandas numpy
```

## Examples

### 1. Time Series Visualization
A line plot displaying the closing prices of Adobe (ADBE) stock over time.

- **Data**: CSV file with `Date` and `Close` columns.
- **Output**: An interactive HTML file named `TimeSeries.html`.

### 2. Stacked Bar Chart
A stacked bar chart comparing the counts of different fruits across three years.

- **Data**: Hardcoded dictionary with fruits and yearly data.
- **Output**: An interactive HTML file displayed in the browser.

### 3. Hexbin Plot
A hexbin plot for visualizing 50,000 randomly generated points.

- **Features**: Uses the `Viridis256` colormap for count-based color mapping.
- **Output**: An interactive plot rendered in the browser.

### 4. Line Plot from CSV
A simple line plot generated from columns `x` and `y` in a CSV file.

- **Data**: CSV file with `x` and `y` columns.
- **Output**: An interactive HTML file named `Line_from_csv.html`.

## Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/bokeh-visualizations.git
   cd bokeh-visualizations
   ```
2. Add your data files (e.g., `adbe.csv`, `data.csv`) to the root directory.
3. Run the Python scripts in your preferred environment (e.g., Jupyter Notebook, command line).
4. Open the generated HTML files in your browser to view the visualizations.

## Dependencies

- **Bokeh**: For creating interactive plots.
- **Pandas**: For data manipulation.
- **NumPy**: For numerical operations.

## Contributing

Feel free to fork this repository, add new examples, or improve existing ones. Submit a pull request for any contributions!

## License

This repository is licensed under the [MIT License](LICENSE). Feel free to use and modify the code as needed.
