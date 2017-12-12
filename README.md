# Unemployment  rate of Blue Collar Workers Modeling

## Description

- A cross-section from 1982

- Number of observations : 4877

- Observation : individuals

- Country : United States

## Usage

1. Data(Benefits)

## Format

A time serie containing :

* **stateur**: state unemployment rate (in %)
* **statemb**: state maximum benefit level
* **state**: state of residence code
* **age**: age in years
* **tenure**: years of tenure in job lost
* **joblost**: a factor with levels (slack\_work,position\_abolished,seasonal\_job\_ended,other)
* **nwhite**: non-white ?
* **school12**: more than 12 years of school ?
* **sex**: a factor with levels (male,female)
* **bluecol**: blue collar worker ?
* **smsa**: lives is smsa ?
* **married**: married ?
* **dkids**: has kids ?
* **dykids**: has young kids (0-5 yrs) ?
* **yrdispl**: year of job displacement (1982=1,..., 1991=10)
* **rr**: replacement rate
* **head**: is head of household ?
* **ui**: applied for (and received) UI benefits ?

## Source

McCall, B.P. (1995) “The impact of unemployment insurance benefit levels on recipiency”, Journal of Business and Economic Statistics, 13, 189–198.

## References

Verbeek, Marno (2004) A Guide to Modern Econometrics, John Wiley and Sons, chapter 7.

Journal of Business Economics and Statistics web site : http://amstat.tandfonline.com/loi/ubes20.


## Gamma Modeling

![alt text](gamma.png)

## Workflow
![alt text](workflow.png)

## Actual data vs Predictions
![alt text](year_comparison.png)

