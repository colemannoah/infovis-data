# Information Visualisation Data

A repository for hosting my cleaned dataset for Information Visualisation

## Original dataset

The original dataset can be found [here](https://github.com/rfordatascience/tidytuesday/blob/master/data/2021/2021-12-21/readme.md)

## Changes made

First I replace the encoded values in the `milk` column with their respective values.

- `0` $\rightarrow$ 'No Milk',
- `1` $\rightarrow$ 'Non-fat Milk',
- `2` $\rightarrow$ '2% Milk',
- `3` $\rightarrow$ 'Soy Milk',
- `4` $\rightarrow$ 'Coconut Milk',
- `5` $\rightarrow$ 'Whole Milk'

I also split the product names to get the main product, not a "subproduct", I also convert the product names to title case just for appearances.

The cleaning was performed in [this notebook](book.ipynb).
