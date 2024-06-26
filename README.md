# Machine-learning-in-R
#### **Overview**
In this project, I used a wide array of baseline predictors (N=80), including psychological, social, biological, sociodemographic, and health variables, from a publicly available dataset to predict recovery or nonrecovery of Generalized Anxiety Disorder (GAD) at a 9-year follow-up.

#### Variables 
###### Predictors 
At baseline, a wide array of predictors was included:

* Sociodemographic Factors: Age, gender, race/ethnicity, marital status, and education.

* Life Challenges: Daily stressors (e.g., work overload, family arguments, traffic problems), chronic stressors (e.g., caregiving, perceived discrimination, perceived inequalities,  work-family spillover, childcare difficulties, unemployment), acute events (e.g., divorce, remarriage, job change, deaths, relocation).

* Health Behaviors: Smoking, alcohol consumption, physical activity, substance abuse, hormone therapy, preventive healthcare, alternative healthcare.

* Psychological: Personality, affect, coping, control, goal orientations, optimism, religion/spirituality, and health beliefs.

* Social: Social support, spousal relations, parent-child ties, childhood violence, social participation, social responsibility, job characteristics, and neighborhood quality.

* Health/Illness: Mental (depression, anxiety, psychological well-being, and cognitive function); physical (subjective health, health comparisons, chronic conditions, symptoms.

* Disability/Functional Limitations and Mortality

* Baseline comorbidity

Variables are described from https://midus.wisc.edu/ 

* Outcome variable: The main outcome was recovery or nonrecovey from GAD at a 9-year follow-up.


#### Analyses

Two machine learning models, gradient boosted trees, and elastic nets were compared to predict recovery or nonrecovery at a 9-year follow-up:
* Logistic regression 
* Gradient boosted trees
* Elastic nets

The elastic net produces standardized coefficients equivalent to the log odds ratios of logistic regression. Shapley values are widely regarded as one of the most effective methods for attributing feature importance in complex models like boosted tree ensembles. These values draw inspiration from game theory principles and provide consistent and accurate measures of feature attribution. For the Gradienmt-Boosted Trees model, Shapley additive explanation (SHAP) values were implemented to quantify the impact of the change in log odds of a particular outcome. 

