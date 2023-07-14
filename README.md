# CO2_Emissions
Detailed EDA and Data Preprocessing on CO2 emissions from various countries over the years 1990-2019

'Carbon_Emission_Dataset.xls' contains three sheets:
1) 'Data'
2) 'Metadata - Countries'
3) 'Metadata - Indicators']

I have worked with sheets (1) and (2).
'Data' sheet has columns:
['Country Name', 'Country Code', 'Indicator Name', 'Indicator Code',
 '1990', '1991', '1992', '1993', '1994', '1995', '1996', '1997', '1998',
 '1999', '2000', '2001', '2002', '2003', '2004', '2005', '2006', '2007',
 '2008', '2009', '2010', '2011', '2012', '2013', '2014', '2015', '2016',
 '2017', '2018', '2019', '2020', '2021']

'Metadata - Countries' sheet has columns:
 ['Country Code', 'Region', 'IncomeGroup', 'SpecialNotes', 'TableName']

Objectives:
- Create a consolidated dataset of CO2 emissions grouped by region and income.
- Handle missing values
- Identify erroneous values/outliers in the dataset
- Treat outliers in the dataset
- Identify countries with highest CO2 emissions in last 5 years
- Identify the top 5 countries in each region with the highest emission in the past 3 years
- Visualization for dataset
