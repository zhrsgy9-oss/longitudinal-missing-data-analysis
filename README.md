# Longitudinal Missing Data Analysis

Analysis and management of missing data in longitudinal studies using R.

## Project Overview

This project focuses on the challenges of handling missing data in longitudinal studies.

The project includes a theoretical review of missing data mechanisms and patterns, followed by the practical implementation and comparison of several methods on a real longitudinal dataset.

The main objective is to investigate how different approaches to missing data may affect statistical estimates in longitudinal analysis.

## Topics Covered

* Longitudinal data and repeated measurements
* Missing data mechanisms:

  * Missing Completely At Random (MCAR)
  * Missing At Random (MAR)
  * Missing Not At Random (MNAR)
* Missing data patterns:

  * Monotone
  * Non-monotone
* Selection Models
* Pattern Mixture Models
* Bayesian approaches to missing data

## Methods

The following approaches were studied and/or implemented:

* Complete Case Analysis (CCA)
* Last Observation Carried Forward (LOCF)
* Multiple Imputation (MI)
* Linear Mixed Models (LMM)
* Generalized Linear Mixed Models (GLMM)

## Practical Analysis

The practical part of the project was conducted using the `sleepstudy` longitudinal dataset from the `lme4` package in R.

The dataset contains repeated measurements of reaction time for 18 participants over 10 days of sleep deprivation.

To evaluate the performance of different methods, missing observations were intentionally introduced under a **MAR mechanism with a monotone dropout pattern**.

The incomplete datasets were then analyzed using different approaches, including:

* Complete Case Analysis
* Last Observation Carried Forward
* Multiple Imputation
* Linear Mixed Models

The resulting estimates were compared with the results obtained from the complete dataset, with particular attention to the bias of the estimated effect of time on reaction time.

## Tools

* **R**
* `lme4`
* Statistical modeling and data analysis

## Author

**Zahra Asgari**

B.Sc. Statistics
Shahid Beheshti University

## Supervisor

**Dr. Ehsan Bahrami Samani**
