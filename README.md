# Employee Attrition Prediction & Inference

## Introduction

In this notebook we are going to be analysing IBM's famous HR Attrition dataset, which has over 30 features to describe the characteristics of around 1400 employees along with a variable to indicate if they ultimately stayed at the company or left.

We have two motivating questions that drive this analysis -
- How well can we predict the likelihood of an employee quitting at a given time using information like their age, gender, experience, compensation, etc?
- What factors have a significant degree of influence on an employee's decision to quit (or stay).

<b>'Why do the answers to these questions matter?', you might ask..</b>

Employee turnover is a problem that companies ranging from small-scale to corporate have been tackling for decades now. Especially in mammoth multinational organizations with operations and projects which run on specialized-skilled manpower, this has proved to be a very costly issue/bottleneck with the costs manifesting not just in capital (training costs, signing bonuses, costs of recruiting a new candidate, and what not) but also in long-term productivity and quality of product/service. 


<b><i>Many studies show that the total cost of losing an employee can range from tens of thousands of dollars to 1.5-2X annual salary</i></b> (That's too depressing a figure to display on a fancy plot).

John Bersin, an HR Expert from Deloitte, in a [LinkedIn post](https://www.linkedin.com/pulse/20130816200159-131079-employee-retention-now-a-big-issue-why-the-tide-has-turned/?src=aff-lilpar&veh=aff_src.aff-lilpar_c.partners_pkw.10078_plc.Skimbit%20Ltd._pcrid.449670_learning&trk=aff_src.aff-lilpar_c.partners_pkw.10078_plc.Skimbit%20Ltd._pcrid.449670_learning&clickid=x7UQhK3m%3AxyOWU6wUx0Mo38XUkizkxVVRUCHyA0&irgwc=1) wrote that, '<i>Employees are appreciating assets that produce more and more value to the organization over time, which helps explain why losing them is so costly</i>'. 

So to answer the questions - 'Why do we need to know the factors that drive/influence an employee to leave' and 'How does the mathematical probability of an employee quitting matter when we could just follow the good old procedure of interview candidates, recruit, train, rinse and repeat all over again everytime an employee quits?' - Because a hike in costs and drop in productivity in addition to the loss of any organization's most precious resource, the employee, are absolutely undesirable. 

Identifying overarching factors which make people want to quit can enable the organization to improve situations related to those factors. Predicting employee churn can be a due dilligence measure in the sense that when the data shows a list of employees with high probability of quitting, the team can find and implement ways to win them back or at the very least, begin the search for a new candidate early such that productivity is not as badly hit as when someone suddenly quits.  

## The Data

We obtained the dataset from [Kaggle](https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset). This is a fictional data set created by IBM data scientists which consists of different factors (of both active and inactive employees) that can influence attrition. 
