# BCGX-Forage-Data-Science-Simulation
This Repository contains various Tasks on Data Science provided by BCGX (Boston Consulting Group, USA) and Forage

The program has 4 modules/Tasks
        
        1: Business Understanding & Hypothesis Framing
        2: Exploratory Data Analysis
        3: Feature Engineering & Modelling
        4: Findings & Recommendations

# Task 1 - Business Understanding & Hypothesis Framing

## Understanding the business context and problem statement.

### The background information on this Task 1:- 

PowerCo, a major gas and electricity provider, seeks to address high customer churn in the SME segment caused by energy market changes. The hypothesis is that price fluctuations drive churn, prompting the need for a predictive model to identify at-risk customers. I was tasked with exploring this hypothesis, and the plan is to use the model on the first day of each month to offer a 20% discount to high-risk customers, discouraging churn.

### Tasks Done:-

In this task, I focused on understanding the client's situation and framing the hypothesis as a data science problem. I outlined the major steps necessary to test this hypothesis effectively. To communicate my findings, I drafted an email to the Associate Director (AD) outlining the required data from the client and the analytical models that should be employed.

### Key steps involved:-

Formulating the hypothesis as a data science problem.
Identifying the factors influencing a customer's decision to stay or switch providers.
Specifying relevant data sources and fields for exploring these factors.
Describing an ideal data frame structure.
Planning exploratory analyses to gain insights into customer churn behavior.

This task aimed to establish a clear direction for our analysis and set the stage for subsequent data-driven actions.

# Task 2 - Exploratory Data Analysis

## Understanding the business through data

### The background information on this Task 2:-

The BCG project team thought that building a churn model to understand whether price sensitivity is the largest driver of churn has potential. The client has sent over some data and the AD wants you to perform some exploratory data analysis.

The data that was sent over included:
  • Historical customer data: Customer data such as usage, sign-up date, forecasted usage, etc
  • Historical pricing data: variable and fixed pricing data etc
  • Churn indicator: whether each customer has churned or not

### Tasks Done:-

#### Sub-Task 1: Data Exploration
Conducted exploratory data analysis to understand the dataset better. Examined data types, statistics, parameters, and variable distributions. This step was essential for gaining a comprehensive dataset understanding.

#### Sub-Task 2: Hypothesis Verification
Investigated the hypothesis that price sensitivity is linked to churn. Defined and calculated price sensitivity metrics to determine any correlation with customer churn.

#### Sub-Task 3: Key Findings and Data Augmentation
Summarized key discoveries in a concise half-page report or slide. Used the provided datasets and links for visualization guidance. Consulted the data description document for column meanings and referred to the task description for project context.


# Task 3 - Feature Engineering & Modelling

## Uncovering signals within the data, predicting churn probability, and evaluating model performance

### The background information on this Task 3:-

The team had a solid grasp of the data and was ready to use it to understand the business problem. The next steps involved brainstorming and creating features to uncover meaningful signals in the data that can inform the churn model. Initially, focus on enhancing the feature related to off-peak price differences in December and January from the previous year. Subsequently, train a Random Forest classifier to predict churn, using rigorous evaluation metrics and justifications for your decisions. Keep in mind the hypothesis that churn is linked to price sensitivity and explore the effectiveness of a 20% discount for high-churn-risk customers with your trained predictive model.

### Tasks to do:-

#### Sub-Task 1: Feature Engineering
Your colleague has created a potentially predictive feature by calculating the "difference in off-peak prices between December and the preceding January."

#### Sub-Task 2: Predictive Modeling
You're responsible for training a Random Forest classifier using the cleaned and engineered dataset. Evaluate the model's performance, explain any underperformance, and justify your choice of evaluation metrics. Additionally, document the pros and cons of using Random Forest in this context. If possible, relate the model's performance to potential client savings with the discount proposition, including the assumptions made for this estimation.

### Tasks Done:-

#### Sub-Task 1:

Evaluated features against labels.
Added complementary new features.
Adjusted feature granularity.
Eliminated unnecessary features.

#### Sub-Task 2:

Determined problem representation (classification/regression).
Defined appropriate model performance expectations.
Specified performance measurement criteria.
Established connections between model performance and business metrics like profits or savings.

# Task 4 - Findings & Recommendations

## Presenting your results and giving recommended actions to the client

### The background information on this Task 4:-

The client wants a quick update on the project's progress.
The AD wants you to draft an abstract (executive summary) of your findings so far.

### Tasks to do:-

Develop an abstract slide synthesizing all the findings from the project so far, keeping in mind that this will be for the key stakeholders meeting which the Head of the SME division, as well as other various stakeholders, will be attending.


### Tasks Done:-

- I assessed the client's expectations, balancing the level of technical detail. 
- I applied the "so what?" test to ensure that any information shared was actionable and valuable for the client.





