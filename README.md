# matplotlib_challenge
In this homework, students are tasked with analyzing the complete data of a pharmacentical company's most recent animal study.  In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. You have been tasked by the executive team to generate all of the tables and figures needed for the technical report of the study. The executive team also has asked for a top-level summary of the study results.

## Table of Contents ##
* [Summary](https://github.com/adriana-icasiano/matplotlib_challenge#Summary)
* [Distribution of Female and Male](https://github.com/adriana-icasiano/matplotlib_challenge#Distribution-of-Female-and-Male)
* [Tumor Volume](https://github.com/adriana-icasiano/matplotlib_challenge#Tumor-volume)

## Summary
A total of 249 mice were studied; however, 1 mouse (mouse ID g989) from the drug regimen Propriva had duplicated data that could not be relied on and was removed from the analysis. Of all the treatments, Capomulin and Ramicane had the highest number of datapoints.

![](https://github.com/adriana-icasiano/matplotlib_challenge/blob/d307db4d349830a158d3c84ddb85cf58b89ab55f/Images/Total%20Number%20of%20Datapoints%20by%20Drug%20Regimen.PNG)

## Distribution of Female and Male
The distribtuion of male (50.4%) and female (49.6%) which implies that the study applied equally across the two sexes. 

![](https://github.com/adriana-icasiano/matplotlib_challenge/blob/d307db4d349830a158d3c84ddb85cf58b89ab55f/Images/Distribution%20by%20Sex.PNG)

## Tumor Volume 
> Looking at a single mouse, it is generally a good sign that the tumor volume declines steadily over the course of the study.
> ![](https://github.com/adriana-icasiano/matplotlib_challenge/blob/d307db4d349830a158d3c84ddb85cf58b89ab55f/Images/Line%20Plot%20of%20Tumor%20Volume%20for%20%20Single%20Mouse.PNG)

>There is a strong positive correlation (0.84) between the weight of the mouse and the average tumor volume, meaning the heavier the mouse, the large the tumor volume.
>![](https://github.com/adriana-icasiano/matplotlib_challenge/blob/d307db4d349830a158d3c84ddb85cf58b89ab55f/Images/Correlation%20betwen%20Weight%20and%20Average%20Tumor%20Volume.PNG)

>Of all the treatments studied, Capomulin and Ramicane have the most similar statistics. These two treatments have the significantly lower mean, median, standard error of mean, variance and standard deviation and zero outliers.  

>![](https://github.com/adriana-icasiano/matplotlib_challenge/blob/c19dc170c1da9fece4c59ace0ad36d900d1c90b8/Images/Statistics.PNG)

>![](https://github.com/adriana-icasiano/matplotlib_challenge/blob/d307db4d349830a158d3c84ddb85cf58b89ab55f/Images/Final%20Tumor%20Volume%20Box%20Plot%20by%20Drug%20Regiment.PNG)
