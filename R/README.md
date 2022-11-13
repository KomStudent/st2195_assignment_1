---
title: Description of Solution
author: Karl Munroe
date: November 13, 2022
---

# Assignment solution to print integers 1 to 10

The solution will present the code in both R and Python to generate integers 1 to 10

### R Code
```{R}

# R Script to print Integers 1 to 10 (including 1 and 10)
# Munroe_Karl
# ST2195
# Assignment 1 part a)

#use the seq() function to generate number sequence

seq(from=1,to=10)

```

### Python Code
```{Python}
"""
title: ST2195 Assignment 1
author: Karl Munroe
Date: November 11, 2022

"""

#begin code

#init variables
strNumList = ""
counter = 0

#loop to generate the output
for i in range(10):
    counter = i + 1 # i will start at 0
    strNumList = strNumList + str(counter) + " " # convert int to str and aapend
print(strNumList) # print the list

#end code

```