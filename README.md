# Leadership Styles and Employee Resistance to Change (SPSS)

A questionnaire study analysed in SPSS: scale reliability, correlations and multiple regression on **95 complete responses**, with every regression assumption tested.


<img width="1392" height="1216" alt="29_spss_regression_results" src="https://github.com/user-attachments/assets/a4a6d385-eb97-4d57-b682-6d03167be00d" />

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

<img width="1527" height="875" alt="31_spss_case_selection_sample" src="https://github.com/user-attachments/assets/0e6c73d1-daba-4ee3-8fc4-0aaf1b8c445d" />
<img width="1650" height="630" alt="32_spss_score_bands" src="https://github.com/user-attachments/assets/aea6a664-fa60-4c79-9bb1-70f961d7b4ea" />

## Results

| Scale | Cronbach's alpha | Reading |
|:--|:--|:--|
| Autocratic leadership | .034 | Poor |
| Transformational leadership | .737 | Acceptable |
| Employee resistance | .058 | Poor |

- **Correlations:** autocratic leadership and resistance are positively related (Pearson r = .261, p = .011; Spearman rho = .205, p = .046). Transformational leadership shows no significant link (r = -.052, p = .616)
- **Regression:** autocratic leadership predicts higher resistance (B = .255, p = .013). Transformational leadership does not (p = .965). R-squared = .068, F(2,92) = 3.36, p = .039
- **Assumptions:** Shapiro-Wilk W = .990 (p = .715), Breusch-Pagan p = .554, VIF = 1.049, largest standardised residual 2.666. All checks passed

<img width="1353" height="728" alt="30_spss_assumption_checks" src="https://github.com/user-attachments/assets/3e187faf-a6e1-4cdf-af29-9f9c4adea27e" />
<img width="1527" height="804" alt="28_spss_correlations" src="https://github.com/user-attachments/assets/96fff6b4-cb7a-460a-a831-2c89386641b9" />
<img width="1527" height="591" alt="27_spss_reliability" src="https://github.com/user-attachments/assets/e20d822f-bc83-44b7-b381-7eb1d7035e84" />
<img width="1122" height="658" alt="35_spss_qq_plot" src="https://github.com/user-attachments/assets/60eaeed8-1c9e-42d4-bbc7-cf161a90a7dc" />
<img width="1122" height="662" alt="34_spss_residual_scatter" src="https://github.com/user-attachments/assets/91180aec-68e6-4258-beae-7f8e2558ec69" />
<img width="749" height="657" alt="33_spss_pp_plot" src="https://github.com/user-attachments/assets/670cffa6-4ca9-4dfc-8ef2-03de7c9a710f" />

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
- LinkedIn: https://www.linkedin.com/in/oluwafemiige/
- Upwork: https://www.upwork.com/freelancers/~015e03cf0fedc8e504
- Fiverr: https://www.fiverr.com/s/3AeGWvx
