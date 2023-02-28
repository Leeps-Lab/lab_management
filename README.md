# Introduction

[Subject Pool Management](#subject-pool-management)

[Orsee Management](#orsee-management)

[Lab Software Tutorial](#lab-software-tutorial)

--- 

## Subject Pool Management

<details><summary>Acquiring Subjects Information</summary>
<p>


First of all, go to "My UCSC". On the top, change “student homepage” to “faculty homepage”. See below:

<p align="center">
    <img height="300px" src="pictures/myucsc1.png" width="450" height="350">
</p>

Then click on “Faculty Center”:

<p align="center">
    <img height="300px" src="pictures/myucsc2.png" width="450" height="200">
</p>

Then From “My schedule”, find out the class number. Go to “search all class rosters”, enter that class number (be careful with the terms, search the right terms you are looking for, otherwise there is not result). You’ll see the list of all students in that class. On the same page, you will find a option to download students' information as an excel sheet, click that to download it. See below:

<p align="center">
    <img height="300px" src="pictures/myucsc3.png" width="450" height="300">
</p>

Now you have downloaded the data you need. Go to next section "Data Cleaning" to find the *R* code to clean the data.

</p>
</details>

<details><summary>Data Cleaning</summary>
<p>

First of all, you need to re-save all the downloaded data to *.csv* file.

```
# first
dta_1 <- read.csv(file = 'D:/zwang/Research/Leeps Lab/2023-winter-recruiting/data/all_data/121.csv')
dta_2 <- read.csv(file = 'D:/zwang/Research/Leeps Lab/2023-winter-recruiting/data/all_data/122.csv')

```

</p>
</details>

<details><summary>Recruiting New Subjects via Email</summary>
<p>

</p>
</details>

## Orsee Management

## Lab Software Tutorial
