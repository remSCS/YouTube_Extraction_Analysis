# YouTube Data Analysis
The goal of this repo is to extract information from the YouTube takeout.

## Demo output
[Click here](viz/watch-history.html) to have an interactive look at the data
![Image](viz/watch-history.png)

## How to use
1. Download your YouTube takeout from [here](https://takeout.google.com/settings/takeout)
2. Extract the zip file to [data/raw/](data/raw/)
3. Run the [extract-watch-history.ipynb](extract-watch-history.ipynb) notebook
4. Get your CSV file from [data/processed/](data/processed/)
5. Run the [visualize-watch-history.ipynb](visualize-watch-history.ipynb) notebook
6. Get your HTML file from [watch-history.html](watch-history.html)