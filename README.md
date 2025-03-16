## Netflix Data Analysis

Netflix has become a major player in the entertainment industry offering a diverse array of TV Shows and Movies to its global audience.

This dataset provides a snapshot of Netflix's content library including various attributes such as titles, genres, release years, ratings and durations.

## Dataset

The dataset used for this analysis is sourced from Kaggle and includes information on Netflix TV Shows and Movies.

**Link to the Dataset :** [Netflix TV Shows and Movies](https://www.kaggle.com/datasets/shivamb/netflix-shows)

## Problem Statement

- To gain insights into the content available on Netflix, understanding the patterns and trends to uncover valuable insights into how the platform curates and evolves its offerings.

- This Exploratory Data Analysis (EDA) aims to address the following key questions :

  - **Content Distribution :** What are the distribution patterns of TV Shows and Movies across different genres and countries? How does the content vary in terms of release year and rating?

  - **Trend Analysis :** Are there observable trends in the release of TV Shows and Movies over time? How has the number of new additions to Netflix's library evolved?

  - **Genre Popularity :** What are the most and least popular genres in Netflix’s library? How does genre popularity differ by region or over time?

  - **Content Characteristics :** What are the typical characteristics (e.g., duration, rating) of TV Shows vs Movies? How do these characteristics vary by genre or release year?

  - **Regional Diversity :** How diverse is Netflix’s content offering in terms of geographic origin? Are there particular regions that contribute more significantly to Netflix’s library?
 
- This analysis will provide a deeper understanding of Netflix content library, revealing trends and patterns that can address future content strategy and development.

<a href='https://www.kaggle.com/code/themrityunjaypathak/netflix-data-analysis'><img src='https://github.com/user-attachments/assets/34fa8078-f967-41f4-b203-e1a0fcf4e0f9'></a>

## Table of Contents

- [Setting up the Enviroment](#setting-up-the-enviroment)
- [Libraries required for the Project](#libraries-required-for-the-project)
- [Getting started with Repository](#getting-started)
- [Steps involved in the Project](#steps-involved-in-the-project)
- [Conclusion](#conclusion)

## Setting up the Enviroment

Jupyter Notebook is required for this project and you can install and set it up in the terminal.

- Install the Notebook
```
pip install notebook
```

- Run the Notebook
```
jupyter notebook
```

## Libraries required for the Project

**NumPy**

- Go to the terminal and run this code
```
pip install numpy
```

**Pandas**

- Go to the terminal and run this code
```
pip install pandas
```

**Matplotlib**

- Go to the terminal and run this code
```
pip install matplotlib
```

**Seaborn**

- Go to the terminal and run this code
```
pip install seaborn
```

## Getting Started

- Clone this repository to your local machine by using the following command :
```bash
git clone https://github.com/TheMrityunjayPathak/Netflix-Data-Analysis.git
```

## Steps involved in the Project

**Importing Libraries**

  - Importing pandas, matplotlib and seaborn libraries

**Reading CSV File**

  - Reading csv file by using pd.read_csv() function

**Overview of the Dataset**

  - Information about shape and size of the dataset
 
  - Columns present in the dataset
 
  - Info about the dataset

**Handling Null values in the Dataset**

  - Filling the null values with most frequent category in the columns

**Changing DataType of Columns**

  - Modifying the datatype of date_added column to pandas datetime format

**Utilizing existing information to create new Columns**

  - Extracting year, month and dates from date_added column
 
  - Splitting listed_in column and selecting first value as genre
 
  - Splitting cast column and selecting first value as lead actor

**Splitting the Dataset**

  - Splitting the dataset based on type of content, i.e TV Shows and Movies

**Statistical Analysis**

  - No. of TV Shows and Movies available on Netflix
 
  - No. of shows in each rating category
 
  - No. of shows released each year, etc.

**Data Visualization**

  - No. of TV Shows and Movies available on Netflix

![download](https://github.com/user-attachments/assets/bd749a85-b52a-49de-98a5-61ac9fc2678b)

  - No. of shows in each rating category

![download](https://github.com/user-attachments/assets/af7869ce-4503-4c6f-9307-a5d448d59d6e)

  - No. of shows uploaded on Netflix each year

![download](https://github.com/user-attachments/assets/a93dd5a9-5381-427c-bef6-87ec41f582b9)

  - No. of shows uploaded on Netflix each month
    
![download](https://github.com/user-attachments/assets/d5f496e6-bb1f-46d0-b647-9131e1d8cb5b)

  - No. of shows uploaded on Netflix each day

![download](https://github.com/user-attachments/assets/8b142693-562d-4c12-b0de-445f69c4a2bf)

  - No. of shows available on Netflix in each country

![download](https://github.com/user-attachments/assets/b3ce1496-cda4-465e-ab1f-26058deb26ca)

  - No. of Movies released on Netflix in each genre

![download](https://github.com/user-attachments/assets/26806eff-d947-4ac6-88d7-43ab4bdf2871)

  - No. of TV Shows released on Netflix in each genre

![download](https://github.com/user-attachments/assets/79a17db7-372e-46ee-bf6f-23e500f7e342)

  - No. of Movies for a lead actor on Netflix

![download](https://github.com/user-attachments/assets/0debdf45-76ce-4701-a719-67b9427cdb97)

  - No. of TV Shows for a lead actor on Netflix
    
![download](https://github.com/user-attachments/assets/8980ee12-992a-450b-b386-48d161e1f841)

  - Avg. length of Movies in each genre

![download](https://github.com/user-attachments/assets/978e7431-0722-4ff3-80bf-2db9354ddb62)

  - Avg. length of TV Shows in each genre

![download](https://github.com/user-attachments/assets/92cf645f-c077-41eb-a3ce-32a2b6c6270c)

  - Distribution of length of Movies on Netflix

![download](https://github.com/user-attachments/assets/d6d66d67-6b74-4c42-9849-5f9c43545507)

  - Distribution of seasons of TV Shows on Netflix

![download](https://github.com/user-attachments/assets/f1008cc9-942c-45de-ac43-9bd2ec078e03)

## Conclusion

- In summary, this analysis has provided valuable insights into Netflix’s content library, revealing trends and patterns that can inform strategic decisions.

- By addressing these insights, Netflix can enhance its content offerings and better meet the needs of its global audience.

<div align='left'>
  
**[`^        Scroll to Top       ^`](#netflix-data-analysis)**

</div>
