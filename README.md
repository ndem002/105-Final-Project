# **CS 105 Project Proposal**
**Group Members:** Christopher Chen, William Mayuga, Noah De Mers, Daniel Boules

**Dataset:** [Data Science and STEM Salaries | *Kaggle*](https://www.kaggle.com/jackogozaly/data-science-and-stem-salaries)

For this project, we will be analyzing a dataset that provides information regarding jobs in STEM.
We want to look at how yearly income might be affected by job experience, education, and various other factors. The information included in this dataset is expansive and will allow us to answer a few questions: 
1. Does having a college degree ultimately increase our yearly income? If so, does the type of degree have any effect on yearly income? 
2. What factors lead to a higher paying job? 
The years spent at a company, their years of experience, level of education, and race are factors we can look into.
3. Based on the number of years of experience you have, the position you want, or your location, what company has employees that match your description?

### Relevant columns from our dataset:
- **company** 
- **title** 
- **totalyearlycompensation**
- **joblocation**
- **yearsofexperience**
- **race related columns**
- **education related columns**

To analyze this data, we are thinking about using the following techniques:

- Finding min, max, and standard deviation of our quantitative data. This is to get an idea of the range of yearly compensation and years of experience.
- Explore how much of the sample have a college degree, and which types of degrees if any, or have simply completed high school. There is also the possibility that an individual never finished high school as well.
- Using chi square tests to find the correlation between each factor and their yearly income. This can help us verify the influence each of them have on income.
- Implement linear regression to find out whether the factors listed under question two affect yearly income and what might have the most substantial and least substantial impact.
- Constructing a recommender system for our third question by using collaborative filtering with K-nearest neighbors. Position title, years of experience, and location can be our features to find a company that will match the description of the user to a company with employees of a similar description.
