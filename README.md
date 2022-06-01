# blog_post_project
The original author is Jinghui Wang. This project is created to partially meet the requirement of Udacity Data Scientist nanodegree.

## Libraries Used
* numpy
* pandas
* matplotlib
* sklearn


## Motivation of the project
The purpose of this project is to investigate the background of bootcamp customers and their expected salaries after graduation, answering the following three questions:

1. What kind of people are more likely to participate in bootcamps?
2. How many years of progamming experiences for the participants going for a bootcamp?
3. What impacts the expected salary after graduation and how?

The stackoverflow data is used for the analysis.

## Description of files in the repo
* background_study.ipynb: examine the background of bootcamp participants in terms of formal eduction, major, career satisfaction, and computer understanding.

* program_experience.ipynb: investigate how many years of programming and coding job experiences the participants may have before going for bootcamp.

* predict_expectedSalary: quantitatively analyze the expected salary after graduation using a linear model.

## Summary of results analysis
* People with bachelor degree are most likely to participate in bootcamp, followed by those having Master degree. Those without any formal education is most unlikely to join bootcamp.
* Half of the participants have the background of computer science or software engineering. Those with computer or quantitative background are more likely take bootcamp trainings. 
* People with higher career satisfaction are more likely to participate in bootcamp.
* Almost 60% of the participants think they don't understand a lot of things about computer so need to get trained to improve.
* People with less than 10 years of programming and coding job experience are more likely to participant in bootcamp, with an exception of those with more than 20 years of experience. It is interesting to check why those with 20 more years of experience are interested in bootcamp.
* The linear model presents underfit problem for expected salary prediction, which requires to be improved in the future if we could have more data that is highly related to the expected salary or use more advanced modeling approaches such as neural network.

