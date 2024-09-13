## Netflix Data Analysis

- Netflix has become a major player in the entertainment industry offering a diverse array of TV Shows and Movies to its global audience.

- This dataset provides a snapshot of Netflix's content library including various attributes such as titles, genres, release years, ratings and durations.

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
 
This analysis will provide Netflix with a deeper understanding of its content library, revealing trends and patterns that can inform future content strategy and development.
 
![download](https://github.com/user-attachments/assets/7943a42f-12c2-4e59-a2cc-9c5396837cfa)

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

- Importing Libraries

  - Importing Pandas, Matplotlib and Seaborn Libraries.

- Reading CSV File

  - Reading CSV File by using pd.read_csv() function.

- Overview of the Dataset

  - Information about shape and size of the Dataset.
 
  - Columns present in the Dataset.
 
  - Info about the Dataset.

- Handling Null values in the Dataset

  - Filling the Null values with most frequent category in the Columns.

- Changing DataType of Columns

  - Modifying the DataType of date_added column to Pandas DateTime Format.

- Utilizing existing information to create new Columns

  - Extracting Year, Month and Dates from date_added Column.
 
  - Splitting listed_in column and selecting first value as Genre.
 
  - Splitting cast column and selecting first value as Lead Actor.

- Splitting the Dataset

  - Splitting the Dataset based on type of Content, i.e TV Shows and Movies.

- Statistical Analysis

  - No. of TV Shows and Movies available on Netflix
 
  - No. of shows in each Rating Category
 
  - No. of shows released each Year, etc.

- Data Visualization

  - No. of TV Shows and Movies available on Netflix

![download](https://github.com/user-attachments/assets/bd749a85-b52a-49de-98a5-61ac9fc2678b)

  - No. of shows in each Rating Category

![download](https://github.com/user-attachments/assets/af7869ce-4503-4c6f-9307-a5d448d59d6e)

  - No. of shows uploaded on Netflix each Year

![download](https://github.com/user-attachments/assets/a93dd5a9-5381-427c-bef6-87ec41f582b9)

## Conclusion

- In summary, this analysis has provided valuable insights into Netflix’s content library, revealing trends and patterns that can inform strategic decisions.

- By addressing these insights, Netflix can enhance its content offerings and better meet the needs of its global audience.

## Link to the Notebook

[Netflix Data Analysis]()

| [Scroll to Top ⬆️](#netflix-data-analysis) |
|:---:|
