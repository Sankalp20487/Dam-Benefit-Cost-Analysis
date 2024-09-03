# Dam Benefit-Cost Analysis

This project involves a Benefit-Cost Analysis (BCA) of two dam construction projects. The analysis assesses the financial viability of each project by generating random values in Excel to model uncertainties in benefits and costs. The project calculates and compares the Benefit/Cost ratios (BCR) for both dams using statistical methods within Excel to evaluate which project offers better financial returns.

## Introduction

The goal of this project is to determine the financial feasibility of two dam construction projects through Benefit-Cost Analysis (BCA). The analysis includes generating 10,000 random values for benefits and costs in Excel to model uncertainty, followed by calculating and comparing Benefit/Cost ratios for both projects.

## Project Structure

- **Data**: All the data, calculations, and analysis are contained within a single Excel file.
- **Reports**: The Excel file also includes graphical representations and summary tables for easy interpretation of the results.

## Methodology

### Monte Carlo Simulation in Excel
- **Random Value Generation**: The project uses Excel’s random number generation functions to create 10,000 simulated values for the benefits and costs of both dams, allowing for the modeling of uncertainty in the estimates.

### Benefit/Cost Ratio (BCR) Calculation
- **BCR Calculation**: The Benefit/Cost ratio is calculated for each of the 10,000 simulations to evaluate the financial return of each project.

### Statistical Analysis in Excel
- **Frequency Distribution**: Frequency distributions of BCR values are created using Excel’s histogram and statistical functions to understand the distribution and variability of the returns for each project.
- **Goodness-of-Fit Test**: A goodness-of-fit test is performed within Excel to determine if a triangular distribution fits the BCR data, using a significance level of 0.05.

## Results

- **BCR Distributions**: The distributions of the BCR values for both dams show a bell-shaped curve, suggesting normality.
- **Statistical Metrics**: Metrics such as mean, variance, skewness, and probability comparisons between the two projects are calculated directly in Excel to aid in decision-making.
- **Goodness-of-Fit**: The triangular distribution was found to be a poor fit for the data based on the p-value calculated in Excel.

## Using the Excel File

To explore the analysis and results:

1. **Open the Excel File**:
   Download and open the Excel file in any compatible spreadsheet software (e.g., Microsoft Excel).

2. **Navigate the Sheets**:
   - **Data**: Contains the randomly generated values for benefits and costs.
   - **Calculations**: Shows the step-by-step calculations for the BCR and other metrics.
   - **Analysis**: Includes the statistical analysis, frequency distributions, and charts.

3. **Review the Results**:
   Explore the visualizations and summary tables to understand the findings of the analysis.

## Conclusion

The comparative analysis between the two dam projects suggests that Dam 1, with a higher mean return and lower skewness, offers a slightly better investment opportunity compared to Dam 2. Despite the similar risk levels between the projects, the analysis indicates a 56.2% probability that Dam 1 will provide a higher return. However, the triangular distribution was not found to be a good fit for modeling the BCR data.

## References

1. Abud, T. P., Augusto, A. G., Fortes, M. Z., Maciel, R. S., & Borba, B. S. M. C. (2022, December 29). State of the Art Monte Carlo Method Applied to Power System Analysis with Distributed Generation. Energies. [Link](https://doi.org/10.3390/en16010394)
2. Frasca. (n.d) Lab: Triangular Probability Distribution. [Video].Panopto. [Link](https://northeastern.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=6f9e314d-3ab0-49bc-8f06-ac9300e649cf&start=2145.860645)
