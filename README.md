# CS484

Our group project repo.

## Team information

|Team Members|Email Address|
|-|-|
|Christopher Yi|cyi11@gmu.edu|
|Rohit Barua|rbarua3@gmu.edu|
|Shafiullah Hashimi|shashim5@gmu.edu|
|Jim Banya|jbanya@gmu.edu|

## Project Proposal

The project proposal can be found [here](https://docs.google.com/document/d/16rTQRJq_3OJXuhi5SyP9XC9JVWHbSFvA59F33fbMlLA/edit).  

## Running the Minority Report Jupyter notebook

We're using tqdm to monitor the progress of our executing code. You'll need to do the following in order to set it up (assuming you're running linux):  

- From the command line interface (CLI), run the following command: `source activate cs484`
- Next, execute the following: `pip install tqdm`.
- ***Optional*** If we're using the time library, we'll also need to run: `pip install time`
- Install the statsmodel library in order to use the statsmodel API. This can be done by running `conda install -c conda-forge statsmodels` or `python -m pip install statsmodels`
- Once done, you can deactivate the environment by typing in the following command: `conda deactivate`

The full environment setup document is available [here](https://github.com/GMU-MinorityReport/CS484/blob/main/documentation/environment_setup_guidance.pdf)

## Data Sources

|Link|Description|
|-|-|
|[Human Resources Diversity Analysis](https://www.kaggle.com/code/jancergomes/human-resources-diversity-analysis)|This dataset analyzes the makeup of various departments across some given organization’s employees. While many of the included analyses seemed to revolve around potential disparities in compensation, the features regarding race, dates hired and the medium through which prospective employees were contacted seem like useful metrics to further explore.|
|[Job Patterns for Minorities and Women](https://www.kaggle.com/datasets/nicholasmarangi/job-patterns-for-minorities-and-women-usa)|This large dataset is itself condensed from data collected by the United States Equal Employment Opportunity Commission (EEOC). It represents a quantitative view of the representation of women and minorities in the private sector from 2011 to 2018. Our hope is to use this data to illustrate any historic trends in representation on an annualized level and to compare this against demographic trends to see if there are any blatant discrepancies|
|[Campus Placement Insights](https://www.kaggle.com/code/vinitshah0110/campus-placement-insights/input)|This data set consists of Placement data of students in our campus. It includes secondary and higher secondary school percentage and specialization. It also includes degree specialization, type and Work experience and salary offers to the placed students|
|[Spatial Regression - Gender Inequality Index](https://www.kaggle.com/code/gianinamariapetrascu/spatial-regression-gender-inequality-index/input?select=pay_gap_Europe.csv)|This dataset analyzes the Gender Inequality Index and the pay gap discrepancies between genders in European countries. It also includes indicators and talks about the importance of spatial regression model and how it can predict the gender gap based on its features.|
|[HR Analytics: Data Leakage](https://www.kaggle.com/code/tanmay111999/hr-analytics-data-leakage-eda-f1-score-80)|IBM HR Analytics is a dataset with more than 30 features that are categorical and discrete with numerical and text data. With the emergence of storing data in digital format as well as recognising it's value, the race of automating the number of outdated systems to improve speed accuracy is on! Thus, this fictional dataset gives us an opportunity to automate employee hiring & firing system of an organization. This is possible with the help of Data Science & Machine Learning techniques.|
|[Levels FYI Dataset: Data Science and Tech Salaries Visualization](https://www.kaggle.com/code/febiec/data-science-and-tech-salaries-visualization/notebook)|This dataset contains useful information about technology jobs across a wide variety of industries from June 2017 to August 2021. We will focus on the following information: total compensation, gender, race, location, education, years of experience and years of tenure.|