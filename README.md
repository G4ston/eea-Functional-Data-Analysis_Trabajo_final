# Functional Data Analysis for Banking Customer Clustering

## Description

This project applies Functional Data Analysis (FDA) to identify clusters within a dataset of banking customers. The dataset contains temporal observations that capture the evolution of financial metrics such as `account balances` and `received transfers`. The project employs B-splines and Fourier bases to model temporal dynamics and their derivatives for extracting characteristic temporal patterns.

The main goal is to segment customers into distinct groups based on their temporal behavior, aiding in understanding client profiles and potentially supporting churn prediction, trend detection, and other data-driven strategies.

## Project Contents

* Data reading and preprocessing
* Conversion of panel data into functional data
* Creation of B-spline and Fourier bases for representing temporal dynamics
* Computation of derivatives for extracting dynamic characteristics
* Functional clustering using the `funFEM` package
* Visualization of clusters and results analysis

## Libraries Used

* `data.table`
* `dplyr`, `tidyr`, `reshape2`
* `fda`, `fdacluster`, `funFEM`
* `ggplot2`

## Results and Conclusions

The clusters generated from the temporal evolution of key variables enable identifying distinct customer behavior patterns. This can support better customer segmentation, churn prevention, trend detection, and other banking analytics applications.

## Getting Started

1. Clone this repository.
2. Install the required libraries.
3. Run the `.Rmd` notebook to replicate the analysis.

## Authors

* Gastón Peña

Feel free to open an Issue or Pull Request if you’d like to collaborate or improve the analysis!

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
