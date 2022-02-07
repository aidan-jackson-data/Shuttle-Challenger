# main-2021-fall

# Statistical Methods for Discrete Response, Time Series, and Panel Data (W271)

This is the main development repository for W271 through which all course material will be dispersed. Students will create their own forks through GitHub Classroom to submit assignments.


## Course Outline
The course is divided into three parts, covering a range of foundational statistical models for modeling discrete response, time-series, and panel data.

### Part 1 (Week 1 – 5): Discrete Response Modeling (DRM)
  * Bernoulli, Binomial, Multinomial, and Poisson probability distributions
  * Maximum likelihood estimation
  * Profile likelihood ratio test
  * Inference for the probability of an event and the use of Wald, Wilson, Agresti-Coull, and Clopper-Pearson confidence intervals
  * Odds, relative risks, and odd ratios
  * Binary logistic regression model
  * Multinomial logistic regression model
  * Poisson regression model
  * Hypothesis testing for regression parameters
  * Log-odds of an event and its relationship to binary logistic regression models
  * Probability of an event in the context of binary logistic regression models
  * Variable (nonlinear) transformation and interactions
  * Contingency tables and the associated inference procedures
  * Test for independency
  * Model specification
  * Model evaluation
  * Model selection

### Part 2 (Week 6 – 10): Time Series Analysis (TSA)
  * Common time series patterns
  * Autocorrelation and partial autocorrelation
  * Notions and measures of stationarity
  * Exploratory time series data analysis
  * Time series regression
  * Akaike’s Information Criterion (and its bias corrected version) and Bayesian Information Criterion (BIC)
  * Model selection based on out-of-sample forecast error
  * Time series smoothing and filtering techniques
  * Stationary and non-stationary time series processes
  * Stationary Autoregressive (AR), Moving Average (MA), and Mixed Autoregressive Moving Average (ARMA) processes
  * ARIMA model
  * Seasonal ARIMA model
  * Estimation, diagnostic checking of model residuals, assumption testing, statistical inference, and forecasting
  * Regression with autocorrelated errors
  * Autoregressive Integrated Moving Average (ARIMA) Model
  * Unit roots, Dickey-Fuller (ADF) test, and Phillips-Perron tests
  * Spurious regression and Co-integration
  * Vector Autoregressive (VAR) Models

### Part 3 (Week 11 – 13): Panel Data Modeling (PDM)
  * Exploratory panel data analysis
  * Pooled OLS regression model
  * First-differenced regression model
  * Distributed lag model
  * Fixed-effect regression model
  * Random-effect regression model
  * Linear mixed-effect model

## Required Textbooks and Other Course Resources
  1.	**[BL]** Christopher R. Bilder and Thomas M. Loughin. Analysis of Categorical Data with R. CRC Press. 2015.
  2.	**[HA]** Rob J Hyndman and George Athanasopoulos. Forecasting: Principles and Practice. The lastest version is https://www.otexts.org/fpp3
  3.	**[CM]** Paul S.P. Cowpertwait and Andrew V. Metcalfe. Introductory Time Series with R. Springer. 2009. (ISBN-10: 978-0-387-88697-8)
  4.	**[W]** Jeffrey Wooldridge. Introductory Econometrics: A Modern Approach. 6th edition. Cengage Learning. (ISBN-10: 130527010X)
  5.	**[BMBW]** Douglas Bates, Martin Machler, Benjamin Bolker, and Steve Walker. Fitting Linear Mixed Effect Models Using lme4
  6.	Additional papers, articles, and readings may be provided throughout the course.


## Class Schedule

* [MIDS Academic](https://www.ischool.berkeley.edu/intranet/students/mics/calendar)
* Fall Break: Sunday, November 7, 2021 – Sunday, November 14, 2021
* MIDS/MICS Virtual Immersion: Monday, November 8, 2021 – Tuesday, November 9, 2021
* Thanksgiving Break: Sunday, November 21, 2021 – Sunday, November 28, 2021

  | Date (Week Beginning)        |Week| Topic | Readings (HA chapters refer to fpp3)  | Homework              |
  |-------------|----|-------|--------------------------------------------------------|-----------------------|
  |Aug 24    | 1| DRM 1 | BL: Ch. 1                                                   |                       |
  |Aug 31    | 2| DRM 2 | BL: Ch. 2.1, 2.2.1 – 2.2.4                                  |Lab 1 released         |
  |Sep 7     | 3| DRM 3 | BL: Ch. 2.2.5 – 2.2.8, 2.3                                  |                       |
  |Sep 14    | 4| DRM 4 | BL: Ch.3 (Skip 3.4.3, 3.5)                                  |Lab 1 due<br>Assignment 1 released |
  |Sep 21    | 5| DRM 5 | BL: Ch.4.1, 4.2.1 – 4.2.3, 5.1 - 5.4 (Skim 5.2.3, 5.3)      |  |
  |Sep 28    | 6| TSA 1 | CM: Ch. 1, 2.1 - 2.3, 4.2; HA: Ch 2                         | Assignment 1 due <br>Assignment 2 released |
  |Oct 5     | 7| TSA 2 | CM: Ch. 5.1 – 5.3; (Optional: CM: Ch. 3.4; HA: Ch. 7-8)     |      |
  |Oct 12    | 8| TSA 3 | CM: 3.1, 3.2, 4.5, 6.1 – 6.4; HA: Ch. 9.1 - 9.4             |Assignment 2 due <br> Lab 2 released        |
  |Oct 19    | 9| TSA 4 | CM: Ch. 4.3 – 4.7, 6, 7.1 – 7.3; HA: Ch. 9.5 – 9.9          |                      |
  |Oct 26    | 10| TSA 5 | CM: Ch.11                                                  |Lab 2 due <br> Assignment 3 released|
  |Nov 2     | 11| PDM 1 | W: Ch. 13 (skip 13.4)                                      |         |
  |Nov 16    | 12| PDM 2 | W: Ch. 14.1 – 14.2                                         |Assignment 3 due <br> Lab 3 released    |
  |Nov 30    | 13| PDM 3 | BMBW                                                       |                     |
  |Dec 7     | 14|       | No Live Session                                            |   Lab 3 due         |

 Sat. May 15: Add/Drop Deadline 

Pre-class concept-check exercises will be due to be completed by 11:59pm on Mondays

Coding exercises will be due to be pushed to your students repository by 4pm on Tuesdays

## Office Hours:  

* Jeffrey: 6 - 6:30pm, 8-8:30pm PT Tuesday (of the Live Sessions
* Rahul: TBD
* Srishti: TBD

## Assessment

  * Three individual assignments, each worth 10%
  * Three group assignments (labs) worth 13%, 12% and 12%
  * Best eleven out of twelve pre-class concept-check exercises, each worth 2% **due Tuesday 4:00pm Pacific Time**
  * Best eleven out of 12 coding exercises (pass/no-pass), each worth 1% **due Mondays 11:59pm Pacific Time**
  
  Note: Any assignment that does not have both a pdf and Rmd file will not be graded.


  | Total Course Score   | Course Grade  |
  |----------------------|---------------|
  |[95,100]              | A             |
  |[90,95)               | A-            |
  |[85,90)               | B+            |
  |[80,85)               | B             |
  |[75,80)               | B-            |
  |[60,75)               | C             |
  |[50,60)               | D             |
  |[0,50)                | F             |

## Student Repository Setup

1. The GitHub Classroom link will be distributed through Slack. Click on the link and _Accept Assignment_. GitHub Classroom automatically forks the main repository for the student (e.g. `2021-fall-<student_name>`).
2. [Clone the fork](https://help.github.com/articles/cloning-a-repository/) using either the GitHub Desktop GUI or command line interface.
3. [Configure](https://help.github.com/articles/configuring-a-remote-for-a-fork/) the upstream remote. This is necessary to merge weekly updates into your personal repository. 
`git remote add upstream https://github.com/MIDS-W271/main-2021-fall.git`
Alternatively you can clone the `main-2021-fall` repository separately.
4. Instructors will update material throughout the semester in the main (aka upstream) repository. [Fetch and Merge](https://help.github.com/articles/syncing-a-fork/) from the remote regularly. Because `main-2021-fall` is a template repository, you will need to use the command
`git merge upstream/main --allow-unrelated-histories`
Alternatively, if you have cloned the main repository, simply pull for updates.
5. To submit weekly homework, students should commit and push their work to `2021-fall-<student_name>`.
