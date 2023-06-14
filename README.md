# Survival_Analysis_in_R_practice
Survival analysis practice in R studio 
(course from Coursera : Survival Analysis in R for Public Health)


variable description
1.	death (0/1)
2.	los (hospital length of stay in nights)
3.	age (in years)
4.	gender (1=male, 2=female)
5.  copd (chronic obstructive lung disease)
6.  prior_dnas (number of outpatient appointments missed in the previous year)
7.  fu_time (follow-up time, i.e. time in days since admission to hospital)

model discription
coxph() : build survival model in R
ggcoxzph() : test proportional assumption
ggcoxfunctional() : test the linearity of continuous variable with the outcome(death)
ggcoxdiagnostics() : test the outlier
