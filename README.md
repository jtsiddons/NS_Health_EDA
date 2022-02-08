# NS Health Data

## Exploratory Data Analysis & Experimentation

Data available at [https://novascotia.ca/dhw/populationhealth/](https://novascotia.ca/dhw/populationhealth/)

Data is extracted from the Annual Notifiable Disease Surveillance Reports using [camelot](https://github.com/camelot-dev/camelot)

The data here is population data no private data of individuals is included, any anonymisation was performed by DHW.

Packages required

* requests (download each pdf)
* camelot (extract table from pdf)
	* tkinter (requirement for camelot)
	* ghostscript (requirement for camelot)
* pandas (data analysis)
* numpy (some computations)
* seaborn (plotting)

There are 2 Jupyter notebooks.

1. Data collection and extraction
2. Data cleaning, processing, and analysis