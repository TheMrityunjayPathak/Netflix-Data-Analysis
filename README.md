## Netflix Data Analysis

Netflix has become a major player in the entertainment industry offering a diverse array of TV Shows and Movies to its global audience.

This dataset provides a snapshot of Netflix's content library including various attributes such as titles, genres, release years, ratings and durations.

## Dataset

The dataset used for this analysis is sourced from Kaggle and includes information on Netflix TV Shows and Movies.

**Link to the Dataset :** [Netflix TV Shows and Movies](https://www.kaggle.com/datasets/shivamb/netflix-shows)

## Problem Statement

- To gain insights into the content available on Netflix, understanding the patterns and trends to uncover valuable insights into how the platform curates and evolves its offerings.

- This Exploratory Data Analysis (EDA) aims to address the following key questions :

  - **Content Distribution :** What are the distribution patterns of TV shows and movies across different genres and countries? How does the content vary in terms of release year and rating?

  - **Trend Analysis :** Are there observable trends in the release of TV shows and movies over time? How has the number of new additions to Netflix's library evolved?

  - **Genre Popularity :** What are the most and least popular genres in Netflix’s library? How does genre popularity differ by region or over time?

  - **Content Characteristics :** What are the typical characteristics (e.g., duration, rating) of TV shows vs movies? How do these characteristics vary by genre or release year?

  - **Regional Diversity :** How diverse is Netflix’s content offering in terms of geographic origin? Are there particular regions that contribute more significantly to Netflix’s library?
 
- This analysis will provide a deeper understanding of Netflix content library, revealing trends and patterns that can address future content strategy and development.

![netflix](https://github.com/user-attachments/assets/34fa8078-f967-41f4-b203-e1a0fcf4e0f9)

## Table of Contents

- [Setting up the Enviroment](#setting-up-the-enviroment)
- [Libraries required for the Project](#libraries-required-for-the-project)
- [Getting started with Repository](#getting-started)
- [Steps involved in the Project](#steps-involved-in-the-project)
- [Conclusion](#conclusion)
- [Link to the Notebook](#link-to-the-notebook)

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

**Pandas**

- Go to Terminal and run this Code
```
pip install pandas
```

- Go to Jupyter Notebook and run this Code from a Cell
```
!pip install pandas
```

**Matplotlib**

- Go to Terminal and run this Code
```
pip install matplotlib
```

- Go to Jupyter Notebook and run this Code from a Cell
```
!pip install matplotlib
```

**Seaborn**

- Go to Terminal and run this Code
```
pip install seaborn
```

- Go to Jupyter Notebook and run this Code from a Cell
```
!pip install seaborn
```

## Getting Started

- Clone the repository to your local machine using the following command :
```
git clone https://github.com/TheMrityunjayPathak/Netflix-Data-Analysis.git
```

## Steps involved in the Project

- **Importing Libraries**

  - Importing Pandas, Matplotlib and Seaborn Libraries

- **Reading CSV File**

  - Reading CSV File by using pd.read_csv() function

- **Overview of the Dataset**

  - Information about shape and size of the Dataset
 
  - Columns present in the Dataset
 
  - Info about the Dataset

- **Handling Null values in the Dataset**

  - Filling the Null values with most frequent category in the Columns

- **Changing DataType of Columns**

  - Modifying the DataType of date_added column to Pandas DateTime Format

- **Utilizing existing information to create new Columns**

  - Extracting Year, Month and Dates from date_added Column
 
  - Splitting listed_in column and selecting first value as Genre
 
  - Splitting cast column and selecting first value as Lead Actor

- **Splitting the Dataset**

  - Splitting the Dataset based on type of Content, i.e TV Shows and Movies

- **Statistical Analysis**

  - No. of TV Shows and Movies available on Netflix
 
  - No. of shows in each Rating Category
 
  - No. of shows released each Year, etc.

- **Data Visualization**

  - No. of TV Shows and Movies available on Netflix

![download](https://github.com/user-attachments/assets/bd749a85-b52a-49de-98a5-61ac9fc2678b)

  - No. of shows in each Rating Category

![download](https://github.com/user-attachments/assets/af7869ce-4503-4c6f-9307-a5d448d59d6e)

  - No. of shows uploaded on Netflix each Year

![download](https://github.com/user-attachments/assets/a93dd5a9-5381-427c-bef6-87ec41f582b9)

  - No. of shows uploaded on Netflix each Month
    
![download](https://github.com/user-attachments/assets/d5f496e6-bb1f-46d0-b647-9131e1d8cb5b)

  - No. of shows uploaded on Netflix each Day

![download](https://github.com/user-attachments/assets/8b142693-562d-4c12-b0de-445f69c4a2bf)

  - No. of shows available on Netflix in each Country

![download](https://github.com/user-attachments/assets/b3ce1496-cda4-465e-ab1f-26058deb26ca)

  - No. of Movies released on Netflix in each Genre

![download](https://github.com/user-attachments/assets/26806eff-d947-4ac6-88d7-43ab4bdf2871)

  - No. of TV Shows released on Netflix in each Genre

![download](https://github.com/user-attachments/assets/79a17db7-372e-46ee-bf6f-23e500f7e342)

  - No. of Movies for a Lead Actor on Netflix

![download](https://github.com/user-attachments/assets/0debdf45-76ce-4701-a719-67b9427cdb97)

  - No. of TV Shows for a Lead Actor on Netflix
    
![download](https://github.com/user-attachments/assets/8980ee12-992a-450b-b386-48d161e1f841)

  - Avg. Length of Movies in each Genre

![download](https://github.com/user-attachments/assets/978e7431-0722-4ff3-80bf-2db9354ddb62)

  - Avg. Length of TV Shows in each Genre

![download](https://github.com/user-attachments/assets/92cf645f-c077-41eb-a3ce-32a2b6c6270c)

  - Distribution of Length of Movies on Netflix

![download](https://github.com/user-attachments/assets/d6d66d67-6b74-4c42-9849-5f9c43545507)

  - Distribution of Seasons of TV Shows on Netflix

![download](https://github.com/user-attachments/assets/f1008cc9-942c-45de-ac43-9bd2ec078e03)

## Conclusion

- In summary, this analysis has provided valuable insights into Netflix’s content library, revealing trends and patterns that can inform strategic decisions.

- By addressing these insights, Netflix can enhance its content offerings and better meet the needs of its global audience.

## Link to the Notebook

[Netflix Data Analysis](https://www.kaggle.com/code/themrityunjaypathak/netflix-data-analysis)

| [Scroll to Top ⬆️](#netflix-data-analysis) |
|:---:|
