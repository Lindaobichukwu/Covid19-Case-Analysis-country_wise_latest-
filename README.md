# Project Title: Covid_19 Case Analysis(country wise latest) Using Python Libraries.
             This is a python analysis on Jupyter notebook using Numpy, Pandas, Seaborn and Matplotlib.


### Data Source:
             This project is a kaggle dataset.


### Project Description: 
             . In this project, I took help from Numpy, Pandas, Seaborn and Matplotlib to create amazing 
               visualizations.
             . This project anaylzes a new coronavirus designated 2019-nCoV was first identified in Wuhan, 
               the capital of China's Hubei province.
             . People developed pneumonia without a clear cause and for which existing vaccines or treatments were 
               not effective.
             . The virus has shown evidence of human-to-human transmission.
             . Transmission rate (rate of infection) appeared to escalate in mid-January 2020.
             . As of 30 January 2020, approximately 8,243 cases have been confirmed.
             . This project reads covid_19 analysis(country wise latest) from an Excel file, processes 
               it, and then generates visualizations to analyze the data.
                     
### Execution: 
               In the course of this project, 
                      . I imported my Libraries: import pandas as pd
                                                import numpy as np
                                                import seaborn as sns
                                                import matplotlib.pyplot as plt
                                                %matplotlib inline
                                                sns.set(color_codes=True)
                                                from sklearn.impute import SimpleImputer
                                              
                       . Imported my dataset: car = df = pd.read_csv('country_wise_latest.csv'))
                    
                       . Explored my dataset: my dataset has  187 rows × 15 columns.

                                             It also contains the following datatypes float64(4), 
                                             int64(9), object(2).
                    
                     . Cleaned and Prepared my dataset: Dropped irrelevant columns, renaming the column names,
                                                        dropping duplicate rows and missing values etc.
                    
                     . Visualized my dataset: 
                                Some of the data visualized are:
                                       . Total sum of death cases.
                                       . Total sum of recovered cases.
                                       . Average of the recovered cases.
                                       . Sorted the confirmed cases in descending order.
                                       . Which countries were highly affected?
                                       . Top 10 countries that were highly affected.
                                       . Sorted the death cases in descending order.
                                       . Analyzed the total sum of affected countries 
                                         across the region by the total death rate across the region.
                                       . Sorted the recovered cases in descending order.
                                       . Sorted the active cases in descending order.
                                       . Analyzed the total number of recovered cases by 
                                         the total number of active persons across the region.
                                       . Total Number of new cases.
                                       . Counted the weekly % increase.
                                       . Analyzed the weekly change and weekly % increase by 
                                         WHO Region.
                                       . Analyzed the deaths and recovery rates.  
                                       . Analyzed the new death rate and the new recovered rate across 
                                         the region.
                                       . Total number of new deaths rate.
                                       . Total number of new recovered.

### Conclusion: 
             . In conclusion, I observed that US, Brazil, United Kingdom, Mexico and 
               Italy had the highest death rates.
             . America had the highest number of confirmed cases and also the highest 
               number of death rate.
             . America also had the highest number of recovered cases and also the 
               highest number of active persons across the region.  
             . The total number of new cases was more in America and South-East Asia.
             . America had the highest number of weekly change while Africa had the 
               most weekly percentage increase recovery.
             . The relative rate of recovered persons were more than that of deaths.
             . The total number of new recovered cases across the region were more 
               than that of the new death cases.¶
