# The Scenario
Cyclistic is a fictional bike-share company in Chicago. The director of marketing believes the company’s future success depends on maximizing the number of annual memberships. Therefore, my team wants to understand how casual riders and annual members use Cyclistic bikes differently. From these insights, my team will design a new marketing strategy to convert casual riders into annual members. But first, Cyclistic executives must approve my recommendations, so they must be backed up with compelling data insights and professional data visualizations.

The Project passes through the following stages before the final recommendations and conclusions could be provided. 
 


## Phase 1: Ask
This phase identifies the key business task to perform and who are the primary and secondary stakeholders of the project.
The Business Task
•	To better understand how annual members and casual riders differ by analyzing historic data trends.
•	To provide recommendations for designing future marketing strategies aimed at converting casual riders to annual members.

### Stakeholders

•	Lily Moreno: The director of marketing and your manager. Moreno is responsible for the development of campaigns and initiatives to promote the bike-share program. 

•	Cyclistic marketing analytics team: My team of data analysts who are responsible for collecting, analyzing, and reporting data that helps guide Cyclistic marketing strategy. 

•	Cyclistic executive team: The notoriously detail-oriented executive team will decide whether to approve the recommended marketing program.

## Phase 2: Prepare
For the purposes of this case study, the datasets are appropriate and will enable you to answer the business questions. The data has been made available by Motivate International Inc. under this [ license](http://https://www.divvybikes.com/data-license-agreement). [Click here](http://https://divvy-tripdata.s3.amazonaws.com/index.html) to see the data.
The data is located on Amazon Aws and organizes in csv file format for each month. The data appears to be credible as it is collected and authorized for public use by the Lyft Bikes and Scooters, LLC (“Bikeshare”) itself. Bikeshare grants a non-exclusive, royalty-free, limited, perpetual license to access, reproduce, analyze, copy, modify, distribute in your product or service and use the Data for any lawful purpose. The data privacy is considered by not disclosing or using any personally identifiable information of the customers. The Data appears to be reliable, original, current, and comprehensive and cited and therefore can be trusted as a good data source.
The data is prepared by downloading and combining into a single data frame using R programming. Information not of use in this analysis were excluded by deleting those columns. The data only of the year 2022 for the 12 months from January to December were downloaded from the source. The files were renamed to follow the best practices. 

## Phase 3: Process
This phase comprised of the data cleaning to remove any bad and duplicate data. The coding of this phase is available in the R notebook attached. R studio was chosen as the data analysis tool for this project as the data set was large and would be daunting and time-consuming to process through spreadsheet. The data cleaning was required as there was missing data at many instances and incomplete data was also found. Some columns were reformatted to change from character to date format. The data was made ready for analysis in this phase. 

## Phase 4: Analysis
The data was aggregated and organized to make it more useful and accessible for analysis. The calculations were performed on the data to identify trends and relationships and a summary of the analysis was prepared and saved as .csv files to be further visualized in tableau. 

### Key Findings:
* Around 60% of trips for the year comprised of annual member while the remaining 40% were done by casual riders. 
* Both casual and annual riders largely prefer classic bikes for their trips but electric bikes were also seen more popular in casual customers. 
* Summers is the most popular season as most trips for both customer groups were recorded during Jun-Aug
* Both casual and members start their trips in afternoon and evening times which means that the customers primarily uses bikeshare during office hours. 
* The peak time for both customer groups was around 6pm.
* Members used rideshare for comparatively shorter trips on average compared to casual riders which recorded average trip length as high as 27 min in May.
* The average trip length was not affected much by the month of the year but declined in december which means in colder months, customers usually prefer shorter rides. 
* Stations such as Kingsbury and Kinzie St together with Clark st &Elm st were most popular among annual members while Casual riders preferred Streeter Dr & Grand Ave followed by DuSable Lakeshore Dr stations most.  


## Phase 5: Share
A final presentation was prepared to discuss the findings from the analysis with the manager. The data analyzed was represented in various visualization created using tableau dashboard. The supporting visualizations and key findings were created in this phase which can be seen on the following [ link to the Dashboard1](https://public.tableau.com/app/profile/amna.amer/viz/CyclisticRideshareAnalysis/Dashboard1) and [Dashboard2](https://public.tableau.com/app/profile/amna.amer/viz/CyclisticRidesharedashboard2/Dashboard2)

## Phase 6: Act
A conclusion was drawn to sum up the differences between the two customer types and final recommendations were provided as a solution to the business task. The deliverables were made and presented. The next steps were discovered and the need for additional data was highlighted such as customer survey to directly discover what drive casual riders to prefer casual over members and vice versa. Following recommendations are provided on the balance of the above analysis:
* Company can offer discounts during the summer season on annual membership specifically on the use of classic or electric bikes to attract more customers. 
* Marketing efforts can be targeted on the top ten stations preferred by the casual riders.
* Extra benefits or loyalty rewards/points could be offered to long trip riders to attract them towards annual membership.
* Marketing efforts can be focused more from 12pm to 6pm around the stations when most casual riders uses their rideshare. 

Furthermore, a survey or questionnaire can be conducted to find why customers prefer a certain type of service. What factors drive their decisions and questions about their age, gender, profession can also be included to better find the target audience through further data analysis.




