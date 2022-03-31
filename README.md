# HR-Analytics-Attrition-Analysis

# Problem Statement
A large company named XYZ, employs, at any given point of time, around 4500 employees. However, every year, around 15% of its employees leave the company and need to be replaced with the talent pool available in the job market. The management believes that this level of attrition (employees leaving, either on their own or because they got fired) is bad for the company, because of the following reasons.

The former employees’ projects get delayed, which makes it difficult to meet timelines, resulting in a reputation loss among consumers and partners.

A sizeable department has to be maintained, for the purposes of recruiting new talent.

More often than not, the new employees have to be trained for the job and/or given time to acclimatise themselves to the company Hence, the management has contracted an HR analytics firm to understand what factors they should focus on, in order to curb attrition. In other words, they want to know what changes they should make to their workplace, in order to get most of their employees to stay. Also, they want to know which of these variables is most important and needs to be addressed right away.


# Goal of the case study
Model the probability of attrition using a logistic regression. The results thus obtained will be used by the management to understand what changes they should make to their workplace, in order to get most of their employees to stay.

# Findings
1. The employees who travel frequently have the largest percentage of attrition, maybe because of the exhaustion caused by business travel.
2. High attrition percentage among employees have bad work-life balance.
3. More satisfaction of work, less attrition percentage
4. More satisfaction of work environment, less attrition percentage
5. Employees have low involvement in the work environment have a higher attrition percentage.
6. It is clear that, employees who have higher income, stay at company longer.
7. It is clear that, employees who have higher increasing in their income, stay at company longer.
8. There is a clear trend, where the employees who work more hours, have the highest attrition
9. Employees who stay at company for a longer period of time have lower attrition rate.
10. Employees who stay at company with the same manager for a longer period of time have lower attrition rate.

# Conclusion
After performing the data preprocessing, model building and validation, it's clear that Random forest is the best model can be deployed to predict how many years may an employee stay at the company before leaving.

Accuracy score for the model is very well, which means the model performed extremely well. Also the other performance Metric's values were greater than 90%.

It's better for RMSE Cross Validation score to be less than 25%, but r2 score is very high. The model has good prediction performance.

The patterns in data can help the management understand why the employee attrition is high, and what can be done to lower it.

During EDA, a lot of insights about Employee Attrition discovered. Some of the main reasons that cause employee attrition to rise is the HR work, bad work-life balance, Frequent Travels etc.

This model can help the management reduce costs related to hiring new employees.
