# R--Analysis
#Load Libraries
library(MASS) 
#View Dataset
carsdatabase
#Create Table
tbl = table(carsdatabase$Model, carsdatabase$Passengers)
tbl # the contingency table
#Chi-squared Statistic
chisq.test(tbl)
