Getting-and-Cleaning-Data
=========================

3rd Course of Data Science Specialization by John Hopkins University on Coursera


Course Project
=========================
1) Unzip the source (https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip) into a folder on your local drive, say "~/datacourse3"

2) Put run_analysis.R into "~/datacourse3/UCI HAR Dataset"

3) In RStudio: setwd("~/datacourse3/UCI HAR Dataset"), followed by: source("run_analysis.R")

4) Use data <- read.table("data_set_with_the_averages.txt") to read the data. Or use write.table(data, "~/datacourse3/cleaned_data.txt",sep="\t",row.name=FALSE) to export this variable as a txt file.
