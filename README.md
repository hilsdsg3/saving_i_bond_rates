<h1 align="center"> Extracting US Treasury Saving I-bond rates </h1>

<br>

## Objective

- [Extract Historical Saving I-bond rates](#helpful_cmd_line_commands)
- [Utilize the Selenium package](#interacting_postgres)
- [Extract the bond rates through html code](#improvements)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

<br>

## Summary

&nbsp;&nbsp;&nbsp; US Treasury Saving I-bonds are safe investments backed by the full faith and credit of the United States governement. The I-bonds are issued by the United States Treasury. The I-bond is abbreviated for Intrest and the bond rates are adjusted two times a year (May 1st, November 1st). You can purchase up to $10,000 worth of I-bonds in a calendar year. Intrest gained from the I-bond is added to the value twice a year. The are a few mre rules and regulations here at [Treasury Direct](https://www.treasurydirect.gov/savings-bonds/i-bonds/).

&nbsp;&nbsp;&nbsp; The project stemmed from a lack of having ready access to the current and historic rates of I-bonds in my cloud database. I use these rates to obtain the annual return on the investments.

&nbsp;&nbsp;&nbsp; For the project we are able to obtain the Fixed and Inflation portion of the bond rate and the Composite. This is achieved by scraping the [Historical bond rates](https://www.treasurydirect.gov/savings-bonds/i-bonds/i-bonds-interest-rates/) using the Selenium package and [regex formulas](https://regex101.com/).

## Chart

You can find the interactive chart below:

<iframe src="[chart.html](https://github.com/hilsdsg3/savings_i_bond_rates/blob/main/chart.html)" width="500" height="400"></iframe>


More coming ....