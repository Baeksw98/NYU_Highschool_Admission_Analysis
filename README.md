# Middle School Data Analysis

Author: Sangwon Baek  
Date: May 25th, 2021  
Course: Introduction to Data Science  
Professor: Pascal Wallisch  

## Overview

This project involves a comprehensive analysis of data related to middle school admissions, focusing on identifying factors that influence admission to High School for Performing and Visual Arts (HSPHS). The study aims to uncover key determinants affecting student admissions and provides recommendations for improving educational outcomes.

## Table of Contents

- [Data Preprocessing](#Data-Preprocessing)
- [Dimension Reduction](#Dimension-Reduction)
- [K-means Clustering](#K-means-Clustering)
- [Findings](#Findings)
- [Actionable Recommendations](#Actionable-Recommendations)

## Data Preprocessing

In this project, missing data was handled by imputing NaN values with the mean values of respective columns. This approach was chosen to maintain as many data points as possible without significantly compromising the dataset's validity.

## Dimension Reduction

Principal Component Analysis (PCA) was performed for dimension reduction. Variables were categorized into predictors, objective achievements, and admissions. The PCA helped reduce 18 variables to 4 uncorrelated factors, significantly simplifying data analysis.

## K-means Clustering

K-means clustering was used to identify patterns in predictors and admission outcomes. The optimal number of clusters was determined through silhouette score analysis, revealing significant factors impacting admissions and objective measures of achievement.

## Findings

The analysis revealed that large schools with more per-student spending and larger class sizes had higher odds of their students being accepted to HSPHS. These factors were statistically significant in determining the admission rates.

## Actionable Recommendations

Based on the findings, recommendations for the New York City Department of Education include enhancing school climate factors and encouraging more applications to HSPHS. Improving the learning environment and fostering a supportive school community are key to boosting student achievements and admission rates.
