# enron-example

Here is the input data and associated final output of a data cleaning exercise with some of the 

The data contains deliveries and receipts for a number of locations/facilities (e.g. ACADIAN, BRIDGELINE) from [Enron](https://en.wikipedia.org/wiki/Enron).  We would like the data to be reformatted into the following data columns: `location`, `date`, `deliveries`, `receipts`, where `date` is a Date format, which should go from `2001-09-01` to `2002-02-05`, with all dates included.  Prior month averages and the month averages can be removed.  