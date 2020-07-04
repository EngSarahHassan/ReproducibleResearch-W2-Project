# ReproducibleResearch-W2-Project
R markdown project for week 2- course Reproducible research 

Code used for obtaining data set:  
```r 
if(!file.exists("data")){dir.create("data")}  
download.file(url="https://d396qusza40orc.cloudfront.net/repdata%2Fdata%2Factivity.zip",destfile = "data/repdata_data_activity.zip")
unzip(zipfile = "data/repdata_data_activity.zip",exdir = "data")

```
