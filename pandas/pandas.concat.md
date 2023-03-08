## Description
Concatenate pandas objects along a particular axis.

Allows optional set logic along the other axes.

Can also add a layer of hierarchical indexing on the concatenation axis, which may be useful if the labels are the same (or overlapping) on the passed axis number.

## Return
object, type of objs
When concatenating all `Series` along the index (axis=0), a `Series` is returned. When `objs` contains at least one `DataFrame`, a `DataFrame` is returned. When concatenating along the columns (axis=1), a `DataFrame` is returned.

## Reference link
* https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.count.html
* https://blog.csdn.net/zzpdbk/article/details/79232661
