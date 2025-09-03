# Statistics Terms 

## **FUNDAMENTAL STATISTICAL CONCEPTS**

### **Population vs Sample**
**Population**: The entire group of individuals or observations about which we want to make inferences. **Sample**: A subset of the population that is actually observed or measured. Statistical inference uses sample data to make conclusions about population parameters.

### **Parameter vs Statistic**
**Parameter**: A numerical characteristic of a population (e.g., population mean μ). **Statistic**: A numerical characteristic calculated from sample data (e.g., sample mean x̄). Statistics are used to estimate parameters.

### **Probability**
A measure of the likelihood that an event will occur, expressed as a number between 0 and 1. Fundamental to statistical inference, hypothesis testing, and quantifying uncertainty in biological data analysis.

### **Distribution**
A mathematical function that describes the frequency or probability of different values in a dataset. Distributions can be discrete (e.g., binomial) or continuous (e.g., normal) and form the basis for statistical modeling and testing.

### **Normal distribution**
A symmetric, bell-shaped probability distribution characterized by its mean and standard deviation. Many biological measurements approximately follow normal distributions, making it central to statistical analysis and the basis for many statistical tests.

### **Mean/Median/Mode**
Measures of central tendency: **Mean** is the arithmetic average; **Median** is the middle value when data is ordered; **Mode** is the most frequently occurring value. Choice depends on data distribution and presence of outliers.

### **Standard deviation/Variance**
Measures of data variability: **Variance** is the average squared deviation from the mean; **Standard deviation** is the square root of variance. Indicate how spread out data points are around the central value.

### **Standard error**
The standard deviation of a sampling distribution, measuring the precision of a sample statistic as an estimate of the population parameter. Smaller standard errors indicate more precise estimates.

## **HYPOTHESIS TESTING FUNDAMENTALS**

### **Null hypothesis (H₀)**
The default assumption that there is no effect, no difference, or no association between variables. Statistical tests attempt to reject the null hypothesis in favor of an alternative hypothesis.

### **Alternative hypothesis (H₁)**
The research hypothesis that contradicts the null hypothesis, representing the effect or difference that researchers are trying to detect. Can be one-sided (directional) or two-sided (non-directional).

### **Significance level (alpha)**
The probability threshold (typically 0.05) for rejecting the null hypothesis. Represents the acceptable risk of making a Type I error (false positive). Lower alpha levels require stronger evidence to reject the null hypothesis.

### **Type I error (α)**
Falsely rejecting a true null hypothesis (false positive). The probability of Type I error equals the significance level alpha. In genomics, this could mean incorrectly identifying a non-associated gene as significant.

### **Type II error (β)**
Failing to reject a false null hypothesis (false negative). The probability of Type II error is beta. In genomics, this could mean missing a truly associated gene. Statistical power equals 1-β.

### **Statistical power**
The probability of correctly rejecting a false null hypothesis (detecting a true effect). Higher power reduces Type II errors and increases the likelihood of detecting real biological effects. Depends on effect size, sample size, and significance level.

### **P-value**
The probability of obtaining results at least as extreme as those observed, assuming the null hypothesis is true. Lower p-values provide stronger evidence against the null hypothesis, but must be interpreted carefully considering effect size and multiple testing.

### **Statistical significance**
A result is considered statistically significant if its p-value is less than the predetermined significance level (usually 0.05). Indicates that the observed result is unlikely to have occurred by chance alone, but doesn't necessarily imply biological importance.

## **EFFECT SIZES AND ESTIMATION**

### **Effect size**
A quantitative measure of the magnitude of a phenomenon or the strength of a relationship between variables. Unlike p-values, effect sizes are not influenced by sample size and provide information about practical significance.

### **Confidence intervals**
A range of values that likely contains the true population parameter with a specified level of confidence (typically 95%). Provides information about both the estimate and its precision, complementing hypothesis testing.

### **Beta coefficient**
In regression analysis, the estimated change in the dependent variable for a one-unit change in an independent variable, holding other variables constant. Indicates the direction and magnitude of association.

### **Log-fold change**
A measure commonly used in genomics to express the ratio of gene expression between conditions on a logarithmic scale. Log₂ fold change of +1 means 2-fold increase, -1 means 2-fold decrease. Preferred over raw fold changes for statistical analysis.

## **MULTIPLE COMPARISONS**

### **Multiple testing correction**
Statistical methods that adjust significance thresholds when performing many statistical tests simultaneously to control the overall false positive rate. Essential in genomics where thousands of genes are tested simultaneously.

### **False discovery rate (FDR)**
The expected proportion of false positives among all significant results. FDR control methods (like Benjamini-Hochberg) are widely used in genomics to balance discovery of true positives while limiting false discoveries.

### **Bonferroni correction**
A conservative multiple testing correction that divides the desired significance level by the number of tests performed. Controls the family-wise error rate but can be overly stringent, leading to reduced statistical power.

### **Family-wise error rate (FWER)**
The probability of making one or more Type I errors across all tests in a study. Bonferroni correction controls FWER, while FDR methods control the expected proportion of false discoveries.

## **STUDY DESIGN AND EXPERIMENTAL CONCEPTS**

### **Randomization**
The random assignment of subjects to different treatment groups or conditions to minimize bias and ensure that groups are comparable. Essential for establishing causal relationships and reducing confounding.

### **Control group**
A comparison group in an experiment that does not receive the treatment or intervention of interest. Allows researchers to isolate the effect of the treatment from other factors.

### **Confounding variables**
Variables that are associated with both the exposure and outcome, potentially creating spurious associations or masking true relationships. Must be controlled through study design or statistical analysis.

### **Bias**
Systematic error that leads to incorrect conclusions. Can occur in study design (selection bias), data collection (measurement bias), or analysis (analytical bias). Threatens the validity of research findings.

## **REGRESSION AND CORRELATION**

### **Correlation**
A statistical measure (typically Pearson's r) that quantifies the strength and direction of linear relationship between two continuous variables. Values range from -1 to +1, with 0 indicating no linear relationship.

### **Linear regression**
A statistical method for modeling the relationship between a dependent variable and one or more independent variables using a linear equation. Provides estimates of association strength and enables prediction.

### **Multiple regression**
Linear regression with multiple independent variables, allowing analysis of complex relationships while controlling for confounding factors. Commonly used in genomics to adjust for covariates like age, sex, and ancestry.

### **Logistic regression**
A regression method for binary outcomes that models the log-odds (logit) of the outcome as a linear function of predictors. Commonly used in case-control studies and for modeling disease risk. Produces odds ratios as effect measures.

### **R-squared (R²)**
The proportion of variance in the dependent variable that is explained by the independent variable(s) in a regression model. Ranges from 0 to 1, with higher values indicating better model fit.

## **STATISTICAL TESTS**

### **t-test**
A statistical test for comparing means between groups or testing if a sample mean differs from a hypothesized value. Assumes normal distribution and equal variances. Common variants include one-sample, two-sample, and paired t-tests.

### **Chi-square test**
A statistical test for analyzing categorical data, commonly used to test for independence between variables or goodness-of-fit to expected distributions. Does not require normal distribution assumptions.

### **ANOVA (Analysis of Variance)**
A statistical method for comparing means across multiple groups simultaneously. Tests whether group means are significantly different while controlling for Type I error inflation that would occur with multiple t-tests.

### **Non-parametric tests**
Statistical tests that don't assume specific data distributions (like normality). Examples include Mann-Whitney U test, Wilcoxon test, and Kruskal-Wallis test. Useful for skewed data or ordinal variables.

### **Bootstrapping**
A resampling method that creates many simulated datasets by sampling with replacement from the original data. Used to estimate sampling distributions, calculate confidence intervals, and assess statistical uncertainty without distributional assumptions.

### **Permutation testing**
A resampling method that creates null distributions by randomly permuting (shuffling) labels or values in the data. Provides exact p-values without distributional assumptions and is commonly used in genomics for testing significance of observed statistics.

## **POWER AND SAMPLE SIZE**

### **Power analysis**
Statistical calculations to determine the probability of detecting an effect of a given size with a specific sample size and significance level. Used prospectively for study planning and retrospectively to interpret negative results.

### **Sample size calculation**
The process of determining the number of subjects needed to achieve adequate statistical power for detecting a meaningful effect. Considers effect size, significance level, power, and variability in the outcome measure.

## **SURVIVAL ANALYSIS**

### **Censoring**
In survival analysis, incomplete observation of event times due to study end, loss to follow-up, or competing events. **Right censoring** (most common) occurs when the event hasn't occurred by the end of observation.

### **Survival analysis**
Statistical methods for analyzing time-to-event data, accounting for censored observations. Commonly used in medical research to study disease progression, treatment effectiveness, and prognosis.

### **Kaplan-Meier estimator**
A non-parametric method for estimating survival probabilities over time from censored data. Produces survival curves that show the probability of survival beyond any given time point.

### **Hazard ratios**
In survival analysis, the ratio of hazard rates between groups, representing the relative risk of the event occurring at any given time. Hazard ratio > 1 indicates increased risk, < 1 indicates decreased risk.

### **Cox proportional hazards model**
A regression method for survival analysis that estimates hazard ratios while adjusting for multiple covariates. Assumes proportional hazards (constant hazard ratios over time) but doesn't require specifying the baseline hazard function.

## **ODDS AND RISK**

### **Odds ratios**
The ratio of odds of an event occurring in one group compared to another group. Commonly used in case-control studies and logistic regression. OR > 1 indicates increased odds, < 1 indicates decreased odds, = 1 indicates no association.

### **Risk ratio (Relative risk)**
The ratio of risk (probability) of an event in one group compared to another group. More intuitive than odds ratios but can only be calculated from cohort studies or randomized trials where incidence can be directly measured.

## **DIAGNOSTIC TEST PERFORMANCE**

### **Sensitivity**
The probability that a test correctly identifies individuals with the condition (true positive rate). High sensitivity means few false negatives. In genomics, refers to the proportion of true associations that are correctly identified.

### **Specificity**
The probability that a test correctly identifies individuals without the condition (true negative rate). High specificity means few false positives. In genomics, refers to the proportion of non-associations that are correctly identified as non-significant.

### **False positive rate**
The probability of incorrectly identifying a negative case as positive (1 - specificity). In hypothesis testing, this is equivalent to the Type I error rate. In genomics, represents the proportion of non-associated genes incorrectly identified as significant.

## **ADVANCED CONCEPTS**

### **Bayesian statistics**
An approach to statistics that incorporates prior knowledge or beliefs about parameters and updates these beliefs with observed data to obtain posterior distributions. Provides probabilistic interpretations and can handle complex models with uncertainty quantification.
