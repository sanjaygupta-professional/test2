# Problem statement & Submission

# Final Group Assignment  
AI/ML Algorithm Playbook by Industry

  
 

## 1. Background & Purpose

As senior leaders, your job is not to tune hyperparameters but to identify high-value business problems, match them to appropriate AI/ML algorithms, and evaluate risks, KPIs, and governance implications.

In this final project, your group will create an “AI/ML Algorithm Playbook” for one industry of your choice, grounded in the classical algorithms covered in this course:

·         Linear Regression

·         Logistic Regression

·         Decision Trees

·         KNN

·         Apriori Algorithm

·         K-Means / K-Medians / K-Modes Clustering

·         Hierarchical Clustering

·         AdaBoost

·         Random Forests

·         ARIMA

You are expected to research real or well-documented use cases, connect them to business value, and explain when and why the algorithm you choose for your task is appropriate.

You may use GenAI tools for discovery and brainstorming, but you must curate sources, cross-check facts, and write your own report in your own language, with proper citations.  
 

## 2. Learning Objectives

·           Map business problems to appropriate algorithms from the course.

·           Explain why an algorithm fits (data type, problem type, interpretability, bias-variance profile).

·           Link models to concrete business KPIs (e.g., revenue, cost, risk, customer metrics).

·           Describe evaluation metrics and validation strategies (confusion matrix, precision/recall, ROC-AUC, MAPE/RMSE, k-fold CV).

·           Discuss risks, limitations, and governance from an executive perspective.  
  
 

## 3. Task Description

### 3.1 Choose One Industry

Examples (not exhaustive):

·         Banking / Financial Services

·         Insurance

·         Retail / e-Commerce

·         Healthcare / Pharma

·         Telecom

·         Manufacturing

·         Logistics / Supply Chain

·         Energy / Utilities

·         Public Sector / Smart Cities

Your playbook will be written for executives in that industry.  
 

### 3.2 Choose One Algorithm Per Group Member

·         Choose one algorithm from the ones covered in the class.

·         Each member of the group must pick a different algorithm.  
  
 

### 3.3 Core Task

1.      For each of the selected algorithms, identify at least one strong use case in your chosen industry (real-world case or realistic synthesis).  Note: each algorithm can have a different use-case, but if you wish to weave all algorithms into addressing a different aspect of a single use case, feel free to do so.

2.      Explain the business problem, data used, why that algorithm is appropriate, which KPIs are impacted, and how you would evaluate and validate the model.

3.      Discuss limitations like overfitting/underfitting, data quality, etc.  
 

## 4. Deliverables

### 4.1 Report (approx. 10-15 pages)

Suggested structure (you may adapt slightly):

·         Executive Summary (1 page): industry, key business problems, high-level mapping of algorithms to problems.

·         Industry and Data Landscape (1-2 pages): overview of industry, typical data sources, key value levers.

·         Algorithm Playbook (6–9 pages): ~1 page per algorithm with use case, KPIs, metrics, validation, and limitations.

·         Cross-Algorithm Comparison (1-2 pages): comparative tables or frameworks on when to use what.

·         References and Appendices: at least 8–10 credible sources and a contribution matrix (which group member contributed what in a tabular format.

### 4.2 Individual Reflection Note (1-2 pages per student)

Each member submits their own note describing the algorithm they owned, what they learned about using it in real business scenarios, how they would apply it in their own organization, and reflections on evaluation, bias–variance, etc., for that algorithm.

This note must be attached as an appendix in the group report; one appendix section per student.  
 

## 5. Roles, Individual Responsibility and Contribution Matrix

Each member is primary owner for exactly one algorithm from the list of 10. The primary owner is responsible for the first draft of that algorithm’s section, ensuring a strong business-grounded use case, and correct metrics and evaluation logic. Other members may help refine and edit, but the primary owner is accountable.

Include in the appendix a Contribution Matrix showing, for each task/section, the primary owner and secondary contributors.  For example:  
 

|   |   |   |
|---|---|---|
|**Task / Section**|**Primary Owner**|**Secondary Contributors**|
|Industry and Data Landscape|A|B|
|Linear Regression section|B|–|
|Logistic Regression section|C|–|
|Decision Trees section|D|–|
|KNN section|E|–|
|…|…|…|
|Cross-Algorithm Comparison|A|All|

## 6. Use of GenAI Tools – Policy  
 

You may use GenAI tools to:

·         Identify potential use cases and relevant sources.

·         Brainstorm and outline your sections.

You must:

·         Verify all facts with independent sources.

·         Cite any reports, articles, or case studies you rely upon.

·         Write your own text; do not paste raw AI-generated content. You are accountable for accuracy and coherence.

Assume you must understand and defend every sentence you submit. If you cannot explain it in class, it should not be in your report.

## 7. Assessment Overview (High-Level)

Your grade will be split into a group component (70%) for the overall quality of the report, and an individual component (30%) for your owned algorithm section, your reflection note, and your documented contribution.

## 8. Rubrics  
 

|   |   |   |
|---|---|---|
|**Criterion**|**Description**|**Points**|
|**Quality and relevance of use cases**|Use cases are real or realistic, clearly described, and strongly tied to the chosen industry; sources are credible and cited.|20|
|**Correct mapping of problems to algorithms**|Demonstrates understanding of **which algorithm fits which problem type** (supervised/unsupervised/time-series, classification vs regression, etc.).|10|
|**Treatment of evaluation and metrics**|Appropriate use of confusion matrix, accuracy, precision, recall, ROC-AUC, regression error metrics, MAPE/RMSE for ARIMA, etc.; correct reasoning.|10|
|**Bias–Variance, overfitting and model validation**|Shows understanding of bias-variance tradeoff, over/underfitting, use of k-fold CV or train–test–validation splits, and monitoring/drift.|10|
|**Cross-algorithm insight**|Clear comparative insights (e.g., when to use Random Forest vs Logistic Regression vs AdaBoost), tradeoffs in interpretability, performance, and business fit.|10|
|**Clarity, structure and executive communication**|Report is well-structured, concise yet rich; presentation is compelling, visually clear, appropriate for executives.|10|

|   |   |   |
|---|---|---|
|**Criterion**|**Description**|**Points**|
|**Quality of individual sections**|Conceptual accuracy, depth, clarity of the algorithm owned by the student (as seen in report body + appendix box).|15|
|**Individual reflection note**|Thoughtfulness, evidence of learning, linkage to own context/organization.|15|

## Appendix: Example of “Good” vs “Weak” Algorithm Section

The following example illustrates the expected difference between a strong (good) and weak treatment of an algorithm. Algorithm: Logistic Regression in the context of credit card default prediction in banking.

### A. Weak Example (What to Avoid)

Logistic Regression is a machine learning algorithm used for classification. In our bank, we can use it to predict which customers will default on their credit cards. We will collect lots of data and train the model. If the accuracy is high, the model is good and we can use it to approve or reject customers. Logistic Regression is good because it is simple and used a lot in the industry. We will check the confusion matrix and try to reduce errors. This will help the bank reduce risk.

Issues with this weak example:

·         Very generic; could be copied from anywhere and is not clearly tied to a concrete business scenario.

·         No specific mention of what data is used (variables, sources, time horizon).

·         Relies only on “accuracy” without discussing class imbalance or cost of false negatives vs false positives.

·         No explicit link to business KPIs (e.g., loss given default, portfolio NPL%, capital requirements).

·         No discussion of regulatory expectations, fairness, or interpretability, which are critical in banking.

·         No mention of validation approach (train-test split, k-fold CV) or bias-variance tradeoff.

### B. Good Example (What We Expect)

Business problem: The bank wants to reduce credit card defaults in its mass retail segment without unnecessarily rejecting profitable customers. We frame this as a binary classification problem: default within 12 months (yes/no).  
  
Data: We use 3 years of historical credit card data for approved customers, including demographics (age, income band, occupation), account behavior (utilization ratio, number of late payments in last 6 and 12 months, overlimit incidents), and bureau variables (existing loans, past delinquencies). The target label is whether the customer became 90+ days past due within 12 months of card issuance.  
  
Why Logistic Regression: The risk team and regulators require an interpretable model where we can explain why a customer was rejected. Logistic Regression provides clear coefficients and odds ratios, allowing us to show, for example, that high utilization and recent delinquencies significantly increase default odds. It is less prone to overfitting than complex non-linear models if we regularize appropriately and keep feature engineering disciplined.  
  
KPIs and evaluation metrics: From a business perspective, we care about reducing the default rate (NPL%) and expected loss (PD × LGD × EAD), while maintaining approval rates. At the model level, overall accuracy is less meaningful because only about 5–7% of customers default. We therefore focus on recall (sensitivity) for the “default” class, precision, and the ROC curve. We use the confusion matrix to understand tradeoffs: a false negative means a defaulted customer we should have flagged; a false positive means a rejected or tightly limited customer who would have paid. We select the probability threshold based on the bank’s risk appetite and cost of misclassification.  
  
Validation and bias-variance: We split data into train/validation/test sets and also run stratified k-fold cross-validation to ensure the model generalizes across different time periods and customer sub-segments. Regularization (e.g., L2) helps control variance. We track performance stability over time to detect drift as economic conditions change.  
  
Risks and limitations: Logistic Regression assumes a linear relationship in the log-odds space and may miss complex interactions between variables. We address this by including interaction terms where business-justified and by regularly back-testing the model. We also check for potential bias across protected groups, and we ensure that any overrides or policy rules are documented for regulatory review. If performance plateaus, we may benchmark against tree-based ensembles, but Logistic Regression remains the baseline model due to interpretability and regulatory comfort.

Why this is a good example:

·         Clearly states the business problem and connects it to a specific portfolio and time horizon.

·         Describes the data used in sufficient detail to be realistic and business-focused.

·         Explains why Logistic Regression is appropriate in terms of interpretability, regulation, and bias-variance profile.

·         Links model behavior to concrete business KPIs and explicitly discusses the confusion matrix and misclassification costs.

·         Shows understanding of validation (train/validation/test, stratified k-fold CV) and overfitting control (regularization).

·         Addresses risks, limitations, and governance aspects such as drift, fairness, and regulatory scrutiny.

Aug term - Foundations of ML & AI - Final Assignment

Submission details

Submission Guidelines

1. Single Submission Per Group:  
Only one member from each group should make the submission. Other group members will not see the submission under their portal; however, mapping has been completed on the backend to ensure proper tracking.

2. Designated File Format:  
Submissions should strictly be in PDF format. Submissions in any other format will not be accepted.

3. Handling Multiple Files:  
If your submission consists of multiple files, please upload all files to a shared drive and provide the drive link in a PDF document. Ensure the access settings are set to "Anyone with the link can view" so the grader can open the files without issues.

4. Submission Changes:  
Submissions cannot be changed once updated, so ensure you upload the correct file. In case of an error, contact student support before the deadline. No files will be updated after the deadline.

5. Support Channels:  
For any queries or assistance, please reach out to the student support channels. We’re here to help!

We strongly recommend you to submit atleast 30 minutes before your deadline

Module Deadline

26 Nov '25

11:59 PM (IST)

Your case study group

![Mike Etuhoko](https://images.upgrad.com/1430ca15-a320-4e09-ad6e-699de28b50a3-full-0g8a5830.jpg)

RK

![sanjay gupta](https://images.upgrad.com/c57fd3fd-d876-4744-afdf-2b2adf4d1607-SanjayGuptaSmile.png)

+2

Upload your file & Save as draft

Upload

Report an error