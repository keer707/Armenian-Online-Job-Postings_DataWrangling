# Armenian Online Job Postings - DataWrangling
> The online job market is a good indicator of overall demand for labor in an economy. This dataset consists of 19,000 job postings from 2004 to 2015 posted on CareerCenter, an Armenian human resource portal.

> Since postings are text documents and tend to have similar structures, text mining can be used to extract features like posting date, job title, company name, job description, salary, and more. Postings that had no structure or were not job-related were removed. The data was originally scraped from a Yahoo! mailing group.

In this project of Data Wrangling of "Armenian Online Job Postings" data from Kaggle, the downloaded zip file is extracted programmatically, assessed and cleaned to prepare the data for further analyses and visualization.

## Required packages
- Pandas
- Numpy
- Matplotlib
- Requests
- zipfile

## Gather
- The data can be found in [Kaggel](https://www.kaggle.com/udacity/armenian-online-job-postings) for downloading zip file. 
- Unzip file programmatically.

![image](https://user-images.githubusercontent.com/34229113/115352945-967fdc80-a1d5-11eb-95cb-89f8d43eccc8.png)

## Assess
Assess data for:
- Quality: inconsistent data, inaccurate data, non-descriptive headers, missing values (NAN)
- Tidiness: issues with structure that prevent easy analysis. Tidy data requirements: Each variable forms a column. Each observation forms a row. Each type of observational unit forms a table.

Types of assessment:
- Visual assessment
- Programmatic assessment (used Pandas)

## Clean
Programmatic data cleaning process:
- Define: convert the assessments into defined cleaning tasks.
- Code: convert those definitions to code and run that code.
- Test: test your dataset, visually or with code, to make sure cleaning operations worked.

#### Data files
- Data : This folder has the zip file to start working through the notebook
- Data_Proccessed : Containes all the files after working through the notebook
