# Correlation Matrices
The R corrplot package is a powerful tool for visualizing correlation matrices: https://cran.r-project.org/web/packages/corrplot/

# What's here
Scripts for streamlining cross-correlation analysis for multiple data sets.

# Theoretical Background
The Pearson coefficient is a basic measure of cross-correlation for time-series data that permits construction of confidence intervals.  Two qualifying assumptions are (1) normality of each time series distribution, and (2) homoscedasticity of the joint distribution between two time series.  The former can be verified using the Shapiro-Wilk test, while the latter can be demonstrated using the Breusch-Pagan test.
