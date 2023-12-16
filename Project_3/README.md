Introduction:

Transferring a health risk prediction model from one group of people to another can be challenging, especially
when the groups are very different. The well-known Framingham Heart Study has created a model that
predicts heart health risks, but it’s mostly been used on people within the study. Our goal is to see if this
model can also work well for people in the NHANES study, which collects health and nutrition data from a
wide range of Americans but doesn’t have longitudinal heart-related health outcomes
This study will use comparisons between data-based and simulation-based approaches to estimate how
well the Framingham model can predict health outcomes for the NHANES group. We’ll do this by using
the detailed health information from NHANES, along with the patterns of heart health outcomes from the
Framingham study, to create a simulated set of results. In doing so, we’ll also carefully apply the Framingham
study’s criteria to the NHANES data. Our analysis aims to show how well the Framingham heart risk model
can be adapted for use with different groups of people.

Package:
| Package       | Latest Version |
|---------------|----------------|
| kableExtra    | 1.3.4      |
| mice          | 3.16.0      |
| gtsummary     | 1.7.2      |
| dplyr         | 1.1.3      |
| tableone      | 0.13.2      |
| MASS          | 7.3.60      |
| fitdistrplus  | 1.1.11     |

File Management:

df_2017.csv <- NHANES data

framingham_df.csv <- Framingham data

proj3_revised.Rmd <- Report code

proj3_revised.pdf <- Report

