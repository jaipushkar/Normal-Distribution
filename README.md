# Normal-Distribution

Overview
This repository contains analysis for two datasets:

Weight-Height Data: Statistical analysis and outlier detection.
Real Estate Prices (Bangalore): Outlier detection and removal for price per square foot data.
Dependencies
This project requires the following Python libraries: pandas, seaborn, matplotlib, numpy, and scipy. Ensure these are installed in your environment.

Analysis Steps
Weight-Height Data
Load Data: The data is read from a CSV file.
Statistical Summary: Basic statistics like mean and standard deviation are computed.
Visualization: A histogram is plotted to visualize the height distribution.
Outlier Detection: Heights are analyzed to find outliers beyond mean ± 3*std.
Real Estate Prices
Load Data: The data is read from an Excel file.
Initial Examination: Basic statistics and distribution are checked for the price_per_sqft column.
Visualization: Histograms are plotted, including one with a log scale to better visualize the distribution.
Outlier Removal: Outliers are removed in two stages:
Percentile Method: Values outside the 0.1th and 99.9th percentiles are removed.
Z-Score Method: Values beyond 4 standard deviations from the mean are removed.
