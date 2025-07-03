# EDA_integration_LLM

## Understanding meaning of each column:Data Dictionary: Variable Description

Survived - Survived (1) or died (0)

Pclass - Passenger’s class (1 = 1st, 2 = 2nd, 3 = 3rd)

Name - Passenger’s name

Sex - Passenger’s sex

Age - Passenger’s age

SibSp - Number of siblings/spouses aboard

Parch - Number of parents/children aboard (Some children travelled only with a nanny, therefore parch=0 for them.)

Ticket - Ticket number

Fare - Fare

Cabin - Cabin

Embarked - Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## Summary

• Developed an AI-powered Gradio application to automate exploratory data analysis—implementing data ingestion, median/mode imputation, descriptive statistics, and correlation visualizations.
• Integrated a local Mistral LLM via Ollama to generate natural-language insights from dataset summaries, enhancing research reporting.
• Optimized preprocessing pipelines in Python (pandas, seaborn, matplotlib) to reduce manual analysis time by 80%.
