# Assessing COVID-19 Severity in US Children with Bayesian Random Time Effect Model

## Abstract
The novel coronavirus disease 2019 (COVID-19) has been widely reported in all age groups including
children, adults and elderly populations in the US. However, relatively little attention on COVID-19
studies were made on understanding the associativity of factors affecting the disease severity among
children.
Using the COVID-19 Case Surveillance Public Use Data, we assess the factors associated with
clinical severity (hospitalization, intensive care unit (ICU) admission, and deaths) among the children
who contracted COVID-19. Descriptive exploratory analyses were conducted using the subset of the data
for children and using observations from March 1 to December 16, 2020. Patterns of missing data in the
dataset were addressed. Bayesian random time effect Poisson models were implemented to estimate the
cumulative weekly adjusted COVID-19-associated incidence rates for all severities. Comparisons between
demographic (sex and race) and clinical (presence of underlying medical conditions) characteristics
among the children patients were made using incidence rate ratios.
Our results revealed that race and ethnicity disparities were noticeably seen among the severity
outcomes in children patients. Black and Hispanic/Latino children's severity outcomes were estimated
to be disproportionately higher than White children which is consistent among many prior studies.
Severity outcomes among children with underlying medical conditions were at least three times more
likely compared to those without. We also find that gender did not provide a significant contribution in
explaining the severity outcomes.

## Data
[COVID-19 data](https://bayesian-covid19-data.s3.eu-north-1.amazonaws.com/COVID19.csv)
COVID-19 Case Surveillance Public Use Data containing individual-level patient records collected by jurisdictions across US states and reported voluntarily to CDC. The available
dataset contains 12 variables for all COVID-19 cases (n = 13, 415, 836) from January 1 to December 16,
2020. The 12 variables included reported times, demographics, exposure history, disease severity indicators
and outcomes, and the presence of underlying medical conditions of de-identified patients.

## Prerequisites
All codes are implemented using the statistical software `R`, version 4.1.1.
Additional installation of `R` packages are contained in each `R` files.

