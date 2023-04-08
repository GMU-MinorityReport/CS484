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

## Data Sources

|Link|Description|
|-|-|
|[Human Resources Diversity Analysis](https://www.kaggle.com/code/jancergomes/human-resources-diversity-analysis)|This dataset analyzes the makeup of various departments across some given organization’s employees. While many of the included analyses seemed to revolve around potential disparities in compensation, the features regarding race, dates hired and the medium through which prospective employees were contacted seem like useful metrics to further explore.|
|[Job Patterns for Minorities and Women](https://www.kaggle.com/datasets/nicholasmarangi/job-patterns-for-minorities-and-women-usa)|This large dataset is itself condensed from data collected by the United States Equal Employment Opportunity Commission (EEOC). It represents a quantitative view of the representation of women and minorities in the private sector from 2011 to 2018. Our hope is to use this data to illustrate any historic trends in representation on an annualized level and to compare this against demographic trends to see if there are any blatant discrepancies|
|[Inequality In Stem](https://www.kaggle.com/code/minkles/inequality-in-stem)|This is a particularly cogent dataset given the team's background. It analyzes the likelihood of entering a STEM field based on a given candidate’s background, including features such as sex, racial background, age, level of education, and etc. While the data is from 2011, any historical trends that can be drawn from then to now can still be a useful analysis metric.|
|[What's in a Name?](https://www.openicpsr.org/openicpsr/project/116023/version/V1/view)|Fictitious resumes sent for help-wanted ads in Boston & Chicago. Studied callbacks based on “White-sounding” vs. “African-American-sounding” names.|
|[Government Labor Statistics](https://www.dol.gov/agencies/wb/data)|A rough schedule for the next five weeks until the midterm presentation is to convene once a week to begin analyzing these datasets through the data mining techniques discussed in lecture. Once we have some form of graphical representation detailing our preliminary results and theories, we will compile them for the video representation. Following the midterm presentation, we will resume the aforementioned schedule to see whether further techniques can help eliminate the causal features that produced any discriminatory results. We will compile these results for a side-by-side comparison of what will hopefully be a marked improvement in representation from what the original data may have depicted.|

## Helpful Tips

We're using tqdm to monitor the progress of our executing code. You'll need to do the following in order to set it up (assuming you're running linux):  

- From the command line interface (CLI), run the following command: `source activate cs484`
- Next, execute the following: `pip install tqdm`.
- ***Optional*** If we're using the time library, we'll also need to run: `pip install time`
- Once done, you can deactivate the environment by typing in the following command: `conda deactivate`

The full environment setup document is available [here](https://github.com/GMU-MinorityReport/CS484/blob/main/documentation/Group_Project_Specs.pdf)
