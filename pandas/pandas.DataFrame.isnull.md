## Description
DataFrame.isnull is an alias for DataFrame.isna.

Detect missing values.

Return a boolean same-sized object indicating if the values are NA. NA values, such as None or `numpy.NaN`, gets mapped to True values. Everything else gets mapped to False values.

Characters such as empty strings `''` or `numpy.inf` are not considered NA values (unless you set `pandas.options.mode.use_inf_as_na=True`).

## Return
DataFrame - Mask of bool values for each element in DataFrame that indicates whether an element is an NA value.

## Reference link
* https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.isnull.html#
* https://blog.csdn.net/weixin_44025103/article/details/124906768
