# -pandas-profiling

Pandas Profiling in Python

The pandas_profiling library in Python include a method named as ProfileReport() which generate a basic report on the input DataFrame. 


# -The report consist of the following:
1. DataFrame overview,
2. Each attribute on which DataFrame is defined,
3. Correlations between attributes (Pearson Correlation and Spearman Correlation), and
4. A sample of DataFrame.


# -For each column, the following information (whenever relevant for the column type) is presented in an interactive HTML report:

1. Type inference: detect the types of columns in a DataFrame
2. Essentials: type, unique values, indication of missing values
3. Quantile statistics: minimum value, Q1, median, Q3, maximum, range, interquartile range
4. Descriptive statistics: mean, mode, standard deviation, sum, median absolute deviation, coefficient of variation, kurtosis, skewness
5. Most frequent and extreme values
6. Histograms: categorical and numerical
7. Correlations: high correlation warnings, based on different correlation metrics (Spearman, Pearson, Kendall, Cramér’s V, Phik, Auto)
8. Missing values: through counts, matrix, heatmap and dendrograms
9. Duplicate rows: list of the most common duplicated rows
10. Text analysis: most common categories (uppercase, lowercase, separator), scripts (Latin, Cyrillic) and blocks (ASCII, Cyrilic)
11. File and Image analysis: file sizes, creation dates, dimensions, indication of truncated images and existence of EXIF metadata
