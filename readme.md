readme.md
Project: Investing

I created this project while researching for automated forms of estimating
the best portfolio for investing in stocks.

This uses mainly Jupyter Notebooks. I can describe the process of what each
notebook does, although, this is only for my own use and I don't expect that
a third party would understand so much of what I have done. On the other hand,
I upload this as a side project to showcase what technologies I use.

Description of the project:

- I connect to the yahoo finance API
- I extract the data of different tickers from the API and saved them on
different csv files.
- I use pandas to read the csv files and calculate various technical parameters,
using 2 methods (1) Bollinger Bands and (2) Ichimoku. Then, I saved the new parameters
into the csv files again.
- Finally, I show the whole information of the selected stocks on matplotlib figures
for further analyses.

