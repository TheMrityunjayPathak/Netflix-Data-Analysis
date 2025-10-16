## Netflix Data Analysis
- Netflix is a leading entertainment platform offering a diverse global library of TV shows and movies.
- This dataset offers a snapshot of its content, including titles, genres, ratings, durations, and more.

<hr>

## Dataset
- The dataset used for this analysis is sourced from Kaggle and includes information on Netflix TV Shows and Movies.
- **Link to the Dataset :** [Netflix TV Shows and Movies](https://www.kaggle.com/datasets/shivamb/netflix-shows)

<hr>

## Problem Statement
- To analyze Netflix content data, uncovering valuable insights into how the platform evolves over time.

<hr>

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

<hr>

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

<hr>

## Getting Started
- Clone this repository to your local machine by using the following command :
```bash
git clone https://github.com/TheMrityunjayPathak/Netflix-Data-Analysis.git
```

<hr>

## Steps involved in the Project

**Importing Libraries**
- Importing necessary libraries like numpy, pandas, matplotlib and seaborn.

**Reading CSV File**
- Reading CSV file by using pd.read_csv() method.

**Overview of the Dataset**
- Information about shape and size of the dataset.
- Types of column present in the dataset (numerical, categorical, text).
- Detailed info about the dataset using df.info() method.

**Handling Null values in the Dataset**
- Filling the null values with most frequent category in categorical columns.

**Changing DataType of Columns**
- Modifying the datatype of date_added column to pandas datetime format.

**Utilizing existing information to create new Columns**
- Extracting year, month and dates from date_added column.
- Splitting listed_in column based on (,) and selecting first value as genre.
- Splitting cast column based on (,) and selecting first value as lead actor.

**Splitting the Dataset**
- Splitting the dataset based on type of content (like TV Shows and Movies).

**Statistical Analysis**
- No. of TV Shows and Movies available on Netflix.
- No. of shows in each rating category.
- No. of shows released each year.

**Data Visualization**

- No. of TV Shows and Movies available on Netflix.

![download](https://github.com/user-attachments/assets/bd749a85-b52a-49de-98a5-61ac9fc2678b)

- No. of shows in each Rating Category.

![download](https://github.com/user-attachments/assets/af7869ce-4503-4c6f-9307-a5d448d59d6e)

- No. of shows uploaded on Netflix each year.

![download](https://github.com/user-attachments/assets/a93dd5a9-5381-427c-bef6-87ec41f582b9)

- No. of shows uploaded on Netflix each month.
    
![download](https://github.com/user-attachments/assets/d5f496e6-bb1f-46d0-b647-9131e1d8cb5b)

- No. of shows uploaded on Netflix each day.

![download](https://github.com/user-attachments/assets/8b142693-562d-4c12-b0de-445f69c4a2bf)

- No. of shows available on Netflix in each country.

![download](https://github.com/user-attachments/assets/b3ce1496-cda4-465e-ab1f-26058deb26ca)

- No. of Movies released on Netflix in each genre.

![download](https://github.com/user-attachments/assets/26806eff-d947-4ac6-88d7-43ab4bdf2871)

- No. of TV Shows released on Netflix in each genre.

![download](https://github.com/user-attachments/assets/79a17db7-372e-46ee-bf6f-23e500f7e342)

- No. of Movies for a lead actor on Netflix.

![download](https://github.com/user-attachments/assets/0debdf45-76ce-4701-a719-67b9427cdb97)

- No. of TV Shows for a lead actor on Netflix.
    
![download](https://github.com/user-attachments/assets/8980ee12-992a-450b-b386-48d161e1f841)

- Avg. length of Movies in each genre.

![download](https://github.com/user-attachments/assets/978e7431-0722-4ff3-80bf-2db9354ddb62)

- Avg. length of TV Shows in each genre.

![download](https://github.com/user-attachments/assets/92cf645f-c077-41eb-a3ce-32a2b6c6270c)

- Distribution of length of Movies on Netflix.

![download](https://github.com/user-attachments/assets/d6d66d67-6b74-4c42-9849-5f9c43545507)

- Distribution of seasons of TV Shows on Netflix.

![download](https://github.com/user-attachments/assets/f1008cc9-942c-45de-ac43-9bd2ec078e03)

<hr>

## Conclusion
Cleaned and analyzed a dataset of 8,000+ Netflix Movies and TV Shows.
- More than 60% of the content on Netflix is rated for mature audiences.
    - Suggests that Netflix targets adult viewers to boost engagement and retention.
- More than 25% of the Movies and TV Shows were released on 1st day of the month.
    - Shows a consistent release schedule, likely aligned with subscription renewal cycles.
- More than 40% of the content on Netflix is exclusive to United States.
    - Shows a strong focus on U.S. market and content availability by location.
- More than 20% of the content on Netflix falls under the "Drama" genre.
    - Confirms that "Drama" is a key part of Netflix's content library.
- More than 23% of the content on Netflix was released in 2019 alone.
    - Indicates a major content push that year, possibly tied to growth or user acquisition efforts.

<div align='left'>
  
**[`^        Scroll to Top       ^`](#netflix-data-analysis)**

</div>
