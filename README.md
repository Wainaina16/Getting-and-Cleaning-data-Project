# Getting and Cleaning Data Project
Author: Andrew Wainaina <br />
# Get the Data
Data Zip File Location: :https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
+ if(!file.exists("./data")){dir.create("./data")}
+ fileUrl <- "https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip"
+ download.file(fileUrl,destfile="./data/Dataset.zip",method="curl")
# Unzip the file
+ unzip(zipfile="./data/Dataset.zip",exdir="./data")



