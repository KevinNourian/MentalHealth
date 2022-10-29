![Alt_Text](https://github.com/KevinNourian/Tech-Mental-Health/blob/main/Images/what-is-mental-health.png)

# Introduction
According to the World Health Organization, Mental health is described as a state of well-being where a person can cope with the normal stresses of life. This state permits productive work output and allows for meaningful contributions to society. In the United States, the Centers for Disease Control and Prevention (CDC) estimates that 1 in 5 adults experience at least one mental health condition every year.

A mentally healthy person is more likely to work efficiently and provide higher-quality work. Historically, there has been a stigma attached to discussing issues related to mental health. This stigma may influence how people deal with mental health issues in their workplace.

In this report, I will analyze the findings of 5 surveys of tech industry workers related to mental health. The surveys were taken in 2014, 2016, 2017, 2018, and 2019. In total, 4218 people from 79 countries participated in the surveys. 

# Goal
The goal of this analysis is to provide some clarity about mental health issues encountered by tech workers in tech companies.

# Technical Requirements

1. Download the data.
2. Load data using SQLite and Pandas.
3. Perform exploratory data analysis.
4. Provide clear explanations.
5. Provide suggestions about how the analysis can be improved.

# Datasets

I used 3 databases from Kaggle's Mental Health in the Tech Industry and concentrated on tech industry workers who work for tech companies:

1. Survey: Contains the year each survey was conducted. The year serves as the SurveyID.
2. Question: Contains 105 questions. Not all questions were used in all the years. Not all questions were given to every individual surveyed. Each question has a unique QuestionID.
3. Answer: Contains 236,898 answers. Participants generally answered more than one question. The answers are in a column called AnswerText.

I did not choose participants who answered No to the question that asked if their primary role in the company is a tech/IT related (QuestionID 9). I did not choose participants who answered No to the question that asked if the employer is primarily a tech company/organization (QuestionID 13).

The total number of participants in my analysis is 909.
