# frailty-depression
Association between physical frailty and incident depression 

Cox proportional hazard models were used to estimate the association between frailty status and depression incidence with follow-up time as the time-dependent variable. Individuals classified as non-frail were used as the reference group, and hazard ratios (HR) and 95% CI were calculated for pre-frail and frail individuals. To evaluate whether the depression risk increased along with the number of frailty indicators, we also established six-category models by treating frailty scores as a categorical variable and using individuals fulfilling no frailty indicator as the reference group. The non-linear effects were examined by introducing a restricted cubic spline into the Cox proportional hazard models. Age, sex, race, alcohol intake, smoking status, sedentary behavior, education level, material deprivation, family income, and metabolic syndrome were treated as covariates being associated with both exposures and outcomes in all models. The proportional hazard assumption was checked using Schoenfeld residuals; no violations were observed. 

To assess the modifying effect of covariates, we included a multiplicative interaction term for each of the 10 covariates and ran further subgroup analyses by covariates showing significant interactions. We also examined the association between five frailty components and depression risks individually (by including only one component of frailty as an exposure variable) and mutually (by including all five components simultaneously).

Linear-mixed effect models were applied to investigate the association of physical frailty and depression symptoms with inflammatory markers and regional GMVs. Within the same analytical framework, physical frailty (or PHQ-9) was fitted as a fixed effect, UK Biobank assessment center as a random effect, and each of the nine inflammatory markers (or regional GMVs) was set as the dependent variable in separate models. The same set of covariates as listed above were used here. We extracted the standardized beta coefficients and converted them to Cohen’s d according to a previous study.

The above codes were tested on R version 4.2.2, operating system, MAC OS, but they can also be run on Windows system
All required packages have been specified in the codes.
No specific installation is required bu only downloading and importing these codes to R.
Expect run time for running the Cox proportional model is about 5 minutes.

