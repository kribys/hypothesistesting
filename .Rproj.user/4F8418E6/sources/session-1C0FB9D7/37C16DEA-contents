#Prompts by Kristian Bysheim, code by ChatGTP Mar 14 version

# check if pacman package is installed, install if necessary
if (!require("pacman")) {
  install.packages("pacman")
}

# install and load most common packages from tidyverse
pacman::p_load(tidyverse)

# download zip file and load data
url <- "https://statisticsbyjim.com/wp-content/uploads/2020/09/HypothesisTestingDatasets.zip"
temp_file <- tempfile()
download.file(url, destfile = temp_file)

# Unzip the contents
unzip(temp_file, exdir = ".")

