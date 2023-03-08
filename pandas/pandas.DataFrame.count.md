## Description
Count non-NA cells for each column or row.

The values None, NaN, NaT, and optionally `numpy.inf` (depending on pandas.options.mode.use_inf_as_na) are considered NA.

## Return
Series or DataFrame
For each column/row the number of non-NA/null entries. If level is specified returns a DataFrame.

## Reference link
* https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.count.html
