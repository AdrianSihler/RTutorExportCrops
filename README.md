This package constitutes an interactive R problem set based on the RTutor package (https://github.com/skranz/RTutor). 

This Problem Set retraces the results of the study “Export Crops and Civil Conflict” by Benjamin Crost and Joseph H Felter. In their article, the researchers examine the impact of fluctuating global market prices in combination with banana cultivation on increasing conflict violence in the Philippines. These insights provide key information for developing countries in the design and execution of agricultural government policies. The article is available here: https://academic.oup.com/jeea/article/18/3/1484/5505371.

## 1. Installation

RTutor and this package is hosted on Github. To install everything, run the following code in your R console.
```s
install.packages("RTutor",repos = c("https://skranz-repo.github.io/drat/",getOption("repos")))

if (!require(devtools))
  install.packages("devtools")

devtools::install_github("AdrianSihler/RTutorExportCrops")
```

## 2. Show and work on the problem set
To start the problem set first create a working directory in which files like the data sets and your solution will be stored. Then adapt and run the following code.
```s
library(RTutorExportCrops)

# Adapt your working directory to an existing folder
setwd("C:/problemsets/RTutorExportCrops")
# Adapt your user name
run.ps(user.name="Jon Doe", package="RTutorExportCrops",
       auto.save.code=TRUE, clear.user=FALSE)
```
If everything works fine, a browser window should open, in which you can start exploring the problem set.
