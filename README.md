# Data Wrangling
Data wrangling exercises covered in Udacity's Data Analyst Nanodegree (Module 4).

Data Wrangling is an essential skill for Data Science, since you cannot have advanced Machine Learning modeling techniques built on top of "messy data".

It can be divided in 3 main tasks:

1. **Gather**: acquiring/collecting data. The very first step in any data-oriented task.

2. **Asses**: evaluate data **quality** and **tidiness**, identifying what needs fixing.
  - **Quality**: low quality data = *dirty data*. Issues with content, such as: missing, invalid (impossible values), inconsistent data (different units). Data should be <u>*clean enough to serve its purpose*</u> - hence it depends on what is is going to be used for.
  - **Tidiness**: untidy data = *messy data*. Issues with structure that should be addresses in order to facilitate analysis, where: !) Each variable forms a column; B) Each observations forms a row; and C) Each type of observational unit forms a table.

3. **Clean**: actions to be taken, according to the previous data assessment, to improve data quality and make the structure properly tidy. This task should be broken down into thre parts:
  - **Define**: a clear action plan - in writing. This "Cleaning Plan" serve as an instruction list for reproducibility.
  - **Code**: translate action plan from words into executable and efficient code.
  - **Test**: assert the cleaning operations performed as intended.

>**Note**: not to be confused with Exploratory Data Analysis (EDA). As a matter of fact, Data Wrangling is all about getting everything ready in order to explore the dataset, looking at descriptive statistics and charts.

This repository contains exercises and small projects focusing on each of the main tasks of Data Wrangling.

## 1) Armenian Online Job Posting database
The [dataset](https://www.kaggle.com/udacity/armenian-online-job-postings) consists of 19,000 job postings between 2004 - 2015, with 24 Columns

