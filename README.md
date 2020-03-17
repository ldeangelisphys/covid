# covid
Dataset for covid-19 confirmed cases and deaths

This dataset was built mainly for a comparison between Netherlands and Italy which at now have the richest set of data. However, in time the dataset was enriched with data from Japan, Republic of Korea, Switzerland, Germany, Denmark and Norway. It also contains the data for China and Hubei province (incomplete).

The dataset is structured in a csv format, where every column encodes the country it is referring to.
The header of the columns must be preserved. Each header should be of the form

CountryName ObservedQuantity
where observed quantities are [Confirmed Cases, Deaths, Tested, ...]

Examples are:
Italy Confirmed Cases
Republic of Korea Deaths
Denmark Confirmed Cases
etc.
