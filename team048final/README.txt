DESCRIPTION:
This package contains all the information necessary to employ an interactive map of air pollution using Tableau's software and to run prediction models using Jupyter notebooks.

Our Pyhton code consists of three different notebooks:
1) data_extraction_and_manipulation : This is mainly for data manipulation and integration, needs the datasets 
        i. pollution_us_2000_2016.csv which is a very large file, you can access here: 
                         https://www.kaggle.com/datasets/sogun3/uspollution/code
        ii. death_data.csv which is shared in CODE folder


2) prection_model_no2: This is for prediction models for average N02 emission level, needs the datasets
        i. The datasets above
        ii. manufaturing_totals_2000_to_2016_restructure.csv which is shared in CODE folder
        iii. CA_county_cars.csv which is shared in CODE folder


3) prediction_model_respiratory_death_counts: This is for prediction models for respiratory death counts, needs the datasets
       i. df3.csv which can be obtained from the last notebook, we also share it in CODE folder

INSTALLATION:
** feel free to use homework instructions or refer to website **
To install Tableau, follow Homework 2's Tableau installation instructions
To setup PySpark, follow Homework 3's PySpark installation instructions

EXECUTION:
These maps can be obtained by the "Map" tableau workbook that we shared after downloading tableau and connecting it to df3.It needs the datasets df3, CA, CA_county_cars, CA_melt, hence we share those datasets in CODE folder. Once you open the workbook, please go to "Mortality vs. Pollutant" and "CA map" dashboards to find the interactive maps you see in the report. In the first dashborard, you can choose different air pollutants and different years to see the value of average air pollutant over the past 10 years and respiratory death count in the year chosen. In the second dashboard, you can find the average of selected air pollutant emission level for the chosen year with the values of number of factories and selected vehicle type.


Everything above can be found in github: 
https://github.com/mander101/cs6242-project-air-pollution/blob/main/team048final