# Information Visualisation Data

A repository for hosting my cleaned dataset for Information Visualisation

## Original dataset

The original dataset can be found [here](https://github.com/rfordatascience/tidytuesday/blob/master/data/2021/2021-09-14/readme.md)

## Changes made

In order to clean this dataset, I drop the `url` column and create my own `song_id` column with a cleaner name for the song - which is the song name concatenated with the performer.

Due to the large amount of data and the fact that the Vega Editor was struggling to render my plots I cut the data down to the last 24 years worth, so the data starts from 01/01/2000.

The cleaning was performed in [book.ipynb](book.ipynb) file. The cleaned dataset has 111,700 rows.
