# Machine-Learning
Udemy course machine learning 

## SECTION 1: ML 101

### What is machine learning?

> A way for a computer to act upon data and make a decision, that previously only a person could make.
> The computer is using a model to be able to produce an answer. 
> The answer could help making business descisions, finding medical problems, etc.

> ML is using an algorithm or computer program to learn about different patterns in data and then take that algorithm (model) and using it to make predictions by feeding it similar data.

> The difference between a normal algorith and a ML model is that instead of just following some actions (algorithm), we are also allowing the machine to learn by giving it input and the desired end result (output). 
> The ML algorithm is taking the input and acts in different ways to try to produce the output. 
> It can try milions of combinations to be able to produce the result.

> ML = Data collection + Data Modeling (Problem definition/Data/Evaluation/Features/Modelling/Experiments) + Deploymnet

**Applications of ML**: 

stocks prediction, self-driving cars, robots, vision procesing, translation services, language processing, etc.

**Goal of ML**: 

make the machines act more like humans

**Simplified path to machine learning**: 

data -> spreadsheets -> relational DBs -> no SQL DBs (Big Data) -> machine learning

**Terms:**

[ Artificial Inteligence [ Machine Learning (ML) [ Deep learning ]]]

[ Artificial Inteligence [ Data Science (DS) [ Machine Learning [ Deep learning ]]]]

DS and ML overlap each other and both use deepl learning and ML techiques => ML, DS specialist is overchanging term (job position)

**Types of ML:**

 - Supervised - the data already has categories: classification (draw a line between the categories), regression (predicitng)
 - Unsupervised - the machine need to create the groups: clustering (decides based on the data), association rule learning
 - Reinforcement learning - the machine learns through trial and error - skill accuisition and real time learning

**Useful links:**

https://teachablemachine.withgoogle.com/

https://ml-playground.com/#

https://github.com/mrdbourke/zero-to-mastery-ml

---
**ENVIRONMENT SETUP**:

Computer -> Project folder [ conda (mini conda = conda + python) + tools (matplotlib, jupyter notebook ...)]

ONLINE: https://cocalc.com/

1. Install miniconda
2. Create a project folder + change into it
3. Create the environment: **conda create --prefix ./env pandas numpy matplotlib scikit-learn jupyter**
4. Activate the environment: **conda activate /path/to/the/project/env** / deactivate: **conda deactivate**
5. Start jupyter: **jupyter notebook**
6. To install additional tools: **conda install tool's_name** 
+ To see a list with the environments: **conda env list**
---
**PANDAS**

![Pandas anathomy](https://github.com/dppeykov/Machine-Learning/blob/master/pandas-anatomy-of-a-dataframe.png)

To import data from a URL: 

**var_name = pd.read_csv("https://...link.csv")**
