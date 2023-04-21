# Group Project
## Covid cases <br />
Data file: https://dev.socrata.com/foundry/data.cdc.gov/9mfq-cb36 <br />
Summary: <br />
COVID-19 data was pulled from the CDC API. The information was reported daily and included both confirmed and unconfirmed cases. The decision was made to use the total of all confirmed and unconfirmed case. <br />
Cleaned up the dates and total sum cases and new cases per day data in order to plot and compare and use to compare against other data sets. <br />
Due to the data being collected daily using the sum total was chosen as this gave us a running total to see the total cases reported and be able visualize it month over month. <br />
The daily data was compiled into month by month totals to better be able to compare against data against some other data sets that were not reported daily <br />

![image](https://user-images.githubusercontent.com/102863554/233518310-75d8ce06-ae95-4b83-87fb-77a9ee1108bf.png)
![image](https://user-images.githubusercontent.com/102863554/233518449-a83497fe-0f99-4124-aa52-d97f950809b0.png)
<br />
## Unemployment rate <br />
Data file: https://beta.bls.gov/dataViewer/view/timeseries/LNS14000000 <br />
Summary: <br />
In order to compare the pre and post impact COVID had to our National Unemployment rate, we pulled data from 2018 to 2021. In that timeframe, we had not seen anything rock employment status the way COVID did. We can see small fluctuations from Jan 2018 to Feb 2020. Between March and April 2020, the Unemployment rate rose to its height at 14.7% and took a 1.5 years to come back down to a pre covid rate. <br />

As new monthly COVID Cases decrease, the Unemployment Rate is trending back to down towards stability. <br />

![image](https://user-images.githubusercontent.com/102863554/233518242-e6e69f0a-d49f-4f17-b957-db0d2cc238c2.png)
![image](https://user-images.githubusercontent.com/102863554/233518266-1e196adf-4ed9-4f9d-8663-25617b21e459.png)
<br />
## GDP <br />
Data file: https://fred.stlouisfed.org/series/GDP <br />
Summary: <br /> 
We were looking at how COVID affected the enrollment amounts in private and public health insurance and the amount of uninsured. To get an understanding of the overall health of the economy we looked at GDP. <br />

What was found was that GDP was growing steadily prior to the start of the COVID outbreak in the U.S. and then took a little dip once it did hit, but then grew rapidly afterwards from the stimulus checks that were sent out to everyone. <br />

![image](https://user-images.githubusercontent.com/102863554/233518103-2c588d95-f7bd-4960-b5d4-fbbaac0b26bb.png)


We looked at a linear regression of COVID vs. GDP to see if there was a correlation, and there was a strong correlation with an r-value of .95. This could cause someone to believe that COVID caused a faster growing GDP, but the stimulus checks that were sent out to everyone to counteract the high unemployment and quarantine effects on the economy. 
![image](https://user-images.githubusercontent.com/102863554/233518491-9c00a283-dc18-4112-9062-6689fe842b0d.png)

## Private Health Insurance <br />

Data file: Datafiles for 2018-2021 can be found at: https://www.census.gov/data/tables/time-series/demo/income-poverty/cps-hi/hi-01.html <br />

Summary: <br />
After a rise in the number of private insured from 2018-2019, there was a decrease in the number of insured. The drop occurred over 2019-2020 to levels below 2018 levels where it continued to decline at a lower rate until the end of 2021. <br />

![image](https://github.com/mike2463/Group-Project/blob/main/Plots/year_total_private_compare.png)

The graph above magnifies the trend in the total number of private insured over the time period, 2018-2021. <br />

There was an overall decrease  in Total Insurance beginning in 2019. Total Insurance decreased as did Employment Based insurance. Increases were noted, however, in the Direct Purchase and Tricare categories. <br />

## Public Health Insurance <br />
Data file: Public Insurance Data.ipynb <br />
Summary: <br />
What trend did public health insurance have between 2018-2022? <br />
There was a slight decrease in public health insurance users from 2018 to 2019. Then the number of public insurance users continued to grow from 2019 to 2021. <br />

![image](https://github.com/mike2463/Group-Project/blob/main/Plots/yeartotal_compare.png)

How did the different types of Health Insurance compare? What did that look like for each year? <br />
For all four years, Medicare and Medicaid have had a lot more users than VA/CHAMPVA.  The number of Medicare users increases each year. Medicaid users show a decline from 2018 to 2019, then an increase from 2019 to 2021. VA/CHAMP slightly fluctuates between each year. <br />

![image](https://github.com/mike2463/Group-Project/blob/main/Plots/public_byyear.png)


## Uninsured <br />
Data file: Uninsured Data.ipynb <br />
Summary: <br />
What trend did the number of uninsured have between 2018-2022? <br />
There was a fluctuation over the four years. There was a slight decrease in uninsured from 2018 to 2019, an increase from 2019 to 2020, then a slight decrease from 2020 to 2021. <br />

![image](https://github.com/mike2463/Group-Project/blob/main/Plots/yearunins_compare.png)


