# blog_post_project
The original author is Jinghui Wang. This project is created to partially meet the requirement of Udacity Data Scientist nanodegree.

## Libraries Used
* numpy
* pandas
* matplotlib
* sklearn

## Motivation of the project
The purpose of this project is to investigate the background and career satisfaction of developers along with their expected salaries after graduation from bootcamp. We are trying to answer the following three questions:

1. What are academic backgrounds of developers?
2. Do developers satisfy their career and how long do they stay in the field?
3. How to predict expected salary after graduation?

The stackoverflow data is used for the analysis.

## Description of files in the repo
* blog_post_project.ipynb: the code file briefly introduces business questions, loads the raw data, cleans data by removing missing values, develops a prediction model for expected salary estimation, and finally evaluates the results by visualization.

## Git
The easiest way to download and install these project is by using git from the command-line:

```diff
# git clone https://github.com/AlexWangVT/blog_post_project.git
```

## Summary of results analysis
* People with bachelor or Master degree are most likely to become a developer. Those without any formal education is least likely to switch to a new career as a software developer.
* Half of the participants have the background of computer science or software engineering. Those with computer or quantitative background are more likely to become a developer than others. 
* More than 70% of the developers satisfy their career with the satisfactory level ranging from 7 to 10.
* More than 60% of the participants think they don't understand a lot about computer but are willing to get further trainings to promote their careers in this field.
* Switching to a new career mostly happen between 10 and 20 years after someone become a develper.
* The linear model presents underfit problem for expected salary prediction, which requires to be improved in the future if we could have more data that is highly related to the expected salary or use more advanced modeling approaches such as neural network.

## Acknowledgement 
The author would like to appreciate Stack Overflow for the data. The data can be found [here](https://www.kaggle.com/datasets/stackoverflow/so-survey-2017). Please feel free to use the code here as you would like!

To see the blog post about this analysis, see the link to my Github page [here](https://alexwangvt.github.io/blog_post_project/).