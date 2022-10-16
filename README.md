# Project 7
When advising clients on market risk, we often need to check multiple organisations for their details. However, sometimes the information is missing or incorrect. Therefore, we want a way to easily check a stock market [(the NZX in New Zealand)](https://www.nzx.com/) and find out which company details are available or missing.
For each company on the [Main board market](https://www.nzx.com/markets/NZSX) we gathered data on the follwing:
* Chief Executive officer
* Media contact information
* Auditor
* Solicitor
* Chief Finacial officer
* Website 
* Screenshot of the website homepage

This data was then input into a Excel spreadsheet and a PDF report was created to summarise the data.

## Quick Start Guide

1.  Download UIPath Extension for **Microsoft Edge**
2.  Make sure all Microsoft Edge Browsers are **closed**
3.  Set number of companies you wish to extract data from. Variable is in `Main.xaml`.

    **MINIMUM VALUE: 2**

    ![image](https://user-images.githubusercontent.com/64149662/195966689-d9ae387f-e803-4037-9f5a-d77c7896562c.png)

4.  In UIPath Select "Run"
5.  Wait for the application to finish running. **This process can take a very long time! Do not manually close anything opened untill its finished.**

## Results

6. Data extracted from NZX is stored in `NZXData.xlsx`
7. Report of companies can be found in `Final Report.pdf`
