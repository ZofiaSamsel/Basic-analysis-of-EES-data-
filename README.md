# Basic-analysis-of-EES-data-
Basic statistical analysis of the European Social Servay 2018 data.

# Information
Data were taken from the ESS survey: https://www.europeansocialsurvey.org/

Data analysis was carried out at different levels of measurement: nominal, ordinal, quantitative, and quotient.

A corresponding analysis was carried out for each set:
(a) Nominal/ ordinal x nominal/ ordinal variable
Cross-tabulation with column percentages; test of independence, i.e. Chi2 test, bootstrapped Chi2, Fisher's exact test; a measure of the strength of association, mosaic or bar/column plot by category of the other variable.

Description of variables:
- ordinal variable psppipla - degree of conviction about the impact on the political system (Not at all; Very
little; Some; A lot; A great deal)
- nominal variable vote01 - did the person vote? (YES, NO)

(b) Nominal/ ordinal x quantitative variable
  Descriptive statistics (means, variances, IQR, etc.) by group by category of the second variable; test of independence, i.e. t-student, ANOVA, regression or their non-parametric equivalents; a measure of the strength of association: R2 from regression; box plot or density plot or histogram of a quantitative variable by grouping by category of nominal/order variable

Description of variables:
- independent variable votes: nominal variable vote01 - whether the person participates in the election
- dependent variable police: quantitative variable trstplc - how much does the person trust the police (NO 0-10 complete trust)
 
 (c) Quantitative x quantitative variable
Descriptive statistics (mean, variance, IQR, etc.) of both variables; Pearson correlation or R2 from regression; scatter plot with a line of best fit

Description of variables:
- independent variable comp: quantitative variable netustm - how much a person uses the computer (in minutes)
- dependent variable confidence: quantitative variable pplhlp - how much do you think that others are likely to try to be helpful, or are they only concerned about themselves? (people only care about themselves 0-10 people are helpful)

Project done for the Statistics course 2022/2023 at the Jagiellonian University.
