# sleep_analysis
Overview
The Sleep Analysis project aims to analyze the impact of daily activities on sleep quality, focusing on factors such as sleep hours, physical activity (e.g.,
walking), screen time, diet, and other lifestyle habits. This project uses R programming language to process, analyze, and visualize data to help users understand 
patterns in their sleep behavior and its relationship to daily habits. This project was completed as part of the [Google analysist course] on Coursera.

# Features
Analyze daily sleep data and associated variables (e.g., hours slept, time to fall asleep, wake time).
Examine the relationship between daily physical activity (e.g., steps walked) and sleep quality.
Assess the effects of screen time, food intake, and other lifestyle factors on sleep duration.
Visualizations of data trends (e.g., daily acitivies, sleep patterns over time).
Statistical analysis to identify significant factors influencing sleep quality.

## Getting Started
# Prerequisites
To run this project, you will need to have the following installed:

R (version 4.0 or higher)
RStudio (optional, but recommended for easier development)
Required R packages (can be installed using install.packages() or devtools::install_github()):
ggplot2 (for visualization)
dplyr (for data manipulation)
tidyr (for data cleaning)
lubridate (for handling dates and times)
readr (for reading data files)
Additional packages for statistical analysis or machine learning if used in your project

## Installation
Install the required R packages
install.packages(c('ggplot2', 'dplyr', 'tidyr', 'lubridate', 'readr'))

# Usage
Load the datasets
View the results in your RStudio environment or save them to a file using functions like ggsave() for plots.
## Dataset
# The dataset used for this analysis contains the following columns:
"Id"                       "ActivityDate"             "TotalSteps"               "TotalDistance"           
"TrackerDistance"          "LoggedActivitiesDistance" "VeryActiveDistance"       "ModeratelyActiveDistance"
"LightActiveDistance"      "SedentaryActiveDistance"  "VeryActiveMinutes"        "FairlyActiveMinutes"     
"LightlyActiveMinutes"     "SedentaryMinutes"         "Calories" 

 # second sleep dataset has conatains the following columns:
 "Id"                 "SleepDay"           "TotalSleepRecords"  "TotalMinutesAsleep" "TotalTimeInBed"

 ## Results & Insights
After analyzing the dataset, you will be able to derive insights like:

Optimal sleep hours for different activity levels.
The effect of physical activity on sleep quality.
How lifestyle factors like screen time or stress correlate with sleep patterns.


 



