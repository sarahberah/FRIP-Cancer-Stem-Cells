# Developmental Evolutionary Modelling

## Team Schedule
- Mondays, Wednesdays, Thursdays @ 2-3pm

## Introduction
The trillions of cells in the human body are developmental descendants from a single fertilized egg. The tissues that arise during this process share many traits in common, from density to gene expression. The degree to which cellular traits are similar often depends on how much developmental history the cells share. In this project, we are using data science tools (e.g., Python, R, Amazon Web Services) to develop an evolutionary developmental model based on embryonic cellular data to assess how much tissue-level trait data (like cancer risk) vary according to their developmental history.

## Research Schedule & Objectives
### Setup
1. Download and install Anaconda: https://www.anaconda.com/products/individual
	- We will use Jupyter Lab to write our code.
2. Create your own github repository (you can store your data science projects here)
3. Create README.md
	- "md" stands for mark down, it is a simple way to format text (# is a header, for example).
	- Think of this as you lab notebook, *detailing all the steps you have done so that your work can be repeated*.
    - Keep this file updated every time you work on your project.

### Week 1
**Load the Data**
1. We will be exploring data from a scientific paper: Tomasetti, Science (2015). The data is saved in the ./data folder.
2. Open fatemap.ipynb, which is a Jupyter Notebook (I have started this for you)

**Clean the Data**
1. Is the Pandas dataframe tidy? (data types correct?, etc.). If not make it so.
    - Remember to drop records with missing data.
2. The data are log transformed, what does this mean and why are they transformed?
3. Perform EDA (exploratory data analysis; plots and summary stats)

### Week 2
**Hypothesis**
1. Create a hypothesis about how life time cancer risk varies with the number of stem cell divisions.
    - what statistical test should you use to test your hypothesis?
        - t-test: average values are different between two groups
        - regression: is one variable influenced by (correlated with) other variables.
        ...
    - Update your README.md with the hypothesis and predictions.
    
**Tests**
1. Use scipy or numpy to create your model/test your hypothesis.
2. Create plots/figures of your data and analysis.

### Week 3
1. Refactor, debug code, and revise figures and Jupyter Notebook based on feedback.
2. Write up project, 1-2 pages, referenced.
	- Discuss the role that evolution played in shaping the data and how this affects your analysis.
3. Create a short 5-7 slide presentation.

### BONUS!
1. If you are up for a challenge, perform a phylogenetic analysis of your data using the tutorials as a guideline.
	This is the proper way to model the data for this project
2. If you want to try this, I will help, just let me know in week 2!!!