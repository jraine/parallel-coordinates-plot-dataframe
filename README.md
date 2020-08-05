# Parallel Coordinates Plot
Produce parallel coordinate plot from pandas dataframe with respect to any value not just class.

In case the pandas.plotting function is a bit too rigid, enables the easy use of some continuous quantity with additional colourbar, instead of assuming class based line grouping.

Additionally can handle categorical data types, and treats columns with only a handful of unique entries as categorical.

Useful for visualising hyperparameter scans for deep learning models, with hyperparameter options saved as columns in a dataframe.

![Image of Parallel Coordinates without spread](https://github.com/jraine/parallel-coordinates-plot-dataframe/blob/master/nospread.png)

Optionally specify a spread to add around categorical points for easier visualisation.

![Image of Parallel Coordinates with spread](https://github.com/jraine/parallel-coordinates-plot-dataframe/blob/master/spread.png)
