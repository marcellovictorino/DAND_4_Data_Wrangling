# Data Wrangling
Data wrangling exercises covered in Udacity's Data Analyst Nanodegree (Module 4).

Data Wrangling is an essential skill for Data Science, since you cannot have advanced Machine Learning modeling techniques built on top of "messy data".

It can be divided in 3 main tasks:

1. **Gather**: acquiring/collecting data and importing that data into your programming environment. Examples: downloading a file, scraping a web page, querying an API etc.

2. **Asses**: evaluate data **quality** and **tidiness**, identifying what needs fixing.
    - **Quality**: low quality data = *dirty data*. Issues with content, such as: missing, invalid (impossible values), inconsistent data (different units). Data should be <u>*clean enough to serve its purpose*</u> - hence it depends on what is is going to be used for.
    - **Tidiness**: untidy data = *messy data*. Issues with structure that should be addresses in order to facilitate analysis, where:
      <ol type='a'> 
      <li>Each variable forms a column;</li>
      <li>Each observations forms a row; and</li>
      <li>Each type of observational unit forms a table.</>
      </ol>

3. **Clean**: actions to be taken, according to the previous data assessment, to improve data quality and make the structure properly tidy. This task should be broken down into three parts:
    - **Define**: a clear action plan - in writing. This "Cleaning Plan" serve as an instruction list for reproducibility.
    - **Code**: translate action plan from words into executable and efficient code.
    - **Test**: assert the cleaning operations performed as intended.

>**Note**: not to be confused with Exploratory Data Analysis (EDA). As a matter of fact, Data Wrangling is all about getting everything ready in order to explore the dataset, looking at descriptive statistics and charts.

This repository contains exercises and small projects focusing on each of the main tasks of Data Wrangling. 

## Project List
<details>
  <summary>1) Armenian Online Job Posting database</summary>
  The [dataset](https://www.kaggle.com/udacity/armenian-online-job-postings) consists of 19,000 job postings between 2004 - 2015, with 24 Columns, full of string descriptions instead of simple categorical values.
</details>

<details>
  <summary>2) Rotten Tomatoes: 100 best movies</summary>
  This project focus on **Data Gathering**, using <code>Beautiful Soup</code> to parse HTML files to extract Critics and Audience Rating; <code>Requests</code> library to access *url* and save data locally: both text and image (using <code>PIL.Image</code> and <code>io.BytesIO</code>) - storing text reviews from Roger Ebert website and Movie Poster images from MediaWiki. Lastly, all datasets are merged to generate rating visualizations and themed WordCloud based on movie review over the poster image.
</details>