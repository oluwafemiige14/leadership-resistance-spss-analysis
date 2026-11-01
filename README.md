# Leadership Styles and Employee Resistance to Change (SPSS)

A questionnaire study analysed in SPSS: scale reliability, correlations and multiple regression on **95 complete responses**, with every regression assumption tested.

![Regression results](assets/29_spss_regression_results.png)

## Research question

Does autocratic or transformational leadership relate to employees' behavioural resistance to change?

## Data and privacy

The study used 100 questionnaires, each with 15 five-point items (autocratic leadership, transformational leadership and employee resistance, 5 items each). **The raw data and SPSS syntax are not included** to protect respondents and the organisation. Only results and charts are shown.

## Approach

1. Removed a duplicate row, coded variables and value labels, and kept the 95 questionnaires complete on all 15 items
2. Built composite scores and score bands (Low 1.00 to 2.33, Moderate 2.34 to 3.67, High 3.68 to 5.00)
3. Tested scale reliability with Cronbach's alpha
4. Ran Pearson and Spearman correlations
5. Ran a multiple regression, then tested normality, constant variance, multicollinearity and outliers

![Case selection and sample profile](assets/31_spss_case_selection_sample.png)
![Score bands](assets/32_spss_score_bands.png)

## Results

| Scale | Cronbach's alpha | Reading |
|:--|:--|:--|
| Autocratic leadership | .034 | Poor |
| Transformational leadership | .737 | Acceptable |
| Employee resistance | .058 | Poor |

- **Correlations:** autocratic leadership and resistance are positively related (Pearson r = .261, p = .011; Spearman rho = .205, p = .046). Transformational leadership shows no significant link (r = -.052, p = .616)
- **Regression:** autocratic leadership predicts higher resistance (B = .255, p = .013). Transformational leadership does not (p = .965). R-squared = .068, F(2,92) = 3.36, p = .039
- **Assumptions:** Shapiro-Wilk W = .990 (p = .715), Breusch-Pagan p = .554, VIF = 1.049, largest standardised residual 2.666. All checks passed

![Reliability](assets/27_spss_reliability.png)
![Correlations](assets/28_spss_correlations.png)
![Assumption checks](assets/30_spss_assumption_checks.png)
![P-P plot](assets/33_spss_pp_plot.png)
![Residual scatterplot](assets/34_spss_residual_scatter.png)
![Q-Q plot](assets/35_spss_qq_plot.png)

## Limitations

- Two of three scales have very low reliability, so results built on them need caution
- Nearly all respondents rated transformational leadership at the top (a ceiling effect)
- The sample is small (95), mostly supervisory staff (about 90%) from one department
- Five questionnaires were excluded for a blank item, and one answer each was missing for gender, age, experience and staff category
- Results show association, not cause, and the model explains only 6.8% of the variance

## How I handled them

- Reported the reliability problem openly instead of hiding it
- Used both Pearson and Spearman correlations so the result does not depend on one method
- Tested every regression assumption before interpreting the model
- Worded conclusions cautiously

## Outcome

In this sample, autocratic leadership is linked to higher resistance to change, and transformational leadership is not. The result is modest and should be read with the reliability limits in mind.

## Tools

SPSS (descriptives, reliability, correlation, regression, residual diagnostics)

## About me

I am **Femi Ige**, a data analyst who turns messy business and research data into Excel dashboards, clean datasets and plain-English recommendations. I trained through the 4-week Data Analyst programme at BeTechified.

- Email: eduwritescholars@outlook.com
- LinkedIn: [add your LinkedIn link]
- Upwork: [add your Upwork link]
- Fiverr: [add your Fiverr link]
