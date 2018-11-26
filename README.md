# Assignement_2.4
x <- c(‘data.science.in.R’, ‘machine.learning.in.R’)
Perform the below string Operation: • Replace the period character "." within each string with another character i.e. "-" minus sign.

ans:Replace the period character "." within each string with another character i.e. "-" minus sign. ->

One of the two ways can be used as mentioned below:

a) gsub(".", "-", x)

b) gsub(".", "-", c(‘data.science.in.R’, ‘machine.learning.in.R’), fixed=TRUE)

x <- c('data.science.in.R','machine.learning.in.R')
Perform the below String Operation: • Append again with “-“ minus sign character at the start of the each string and finally concatenate all the

string within the vector to form a final single string and assigning it the object.

ans:paste(paste0("-", gsub("\.", "-", c('datascience.in.R’, ‘machine.learning.in.R’))), collapse=" ")
