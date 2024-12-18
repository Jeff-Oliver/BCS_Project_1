
# BCS_Project_1

## Team 6 Movie analysis


## Let's make a movie

### Project Description

In this project, we will be analyzing popular movies over the last 10 years to identify the key factors that contributes to a movie's success.

In the process, we will also be able to determine trends in genre popularity over the years, movies budgets, viewers ratings, revenues based on genres and other analyses in the motion picture industry.

These insights are important for filmmakers, producers, casts and even the audience.



### Technology Requirements

- **VS Code/Jupyter Notebook/Google colab**: For documentation and interactive data analysis.
- **Python**: For data mining, analysis, modeling and processing.
- **Pandas & Numpy**: For data cleaning, manipulation and numerical computing.
- **Matplotlib**: For data visualization and colormap handling.
- **Seaborn**: For statistical data visualization



### Dataset

The data set used in this project is relevant as it provides detailed information on movies released in the last 10 years. Such information includes data on movie titles, genres, budget, ratings etc. These are important data in our analysis and making our prediction.

**Source**: [https://www.kaggle.com/datasets/asaniczka/tmdb-movies-dataset-2023-930k-movies]



### Technology installation and Setup.

1. Clone the repository:
```bash 
git clone https://github.com/Jeff-Oliver/BCS_Project_1.git
```

2. Navigate to the project's directory:
```bash
cd BCS_Project_1
```

3. Install the technology requirements:
```bash
pip install -r technology requirements.text
```

4. Launch your preferred notebook
```bash
jupyter/VS_Code/Google_Colab notebook
``` 


### Application instructions

- Open the `analysis.ipynb` notebook
- Run the top cells to import the dependancies 
- Run the read data frame cell to load and view the dataset
- Run the visualization and insights cells to view the patterns in the movies



### Project Structure

```
├──requirements.txt           # Dependancies
├── data/
│   ├── raw_data.csv          # Raw dataset
│   ├── cleaned_data.csv      # Cleaned dataset
├── notebooks/
│   ├── Movie_Success_Analysis.ipynb  # Jupyter Notebook
├── src/
│   ├── analysis.py           # Analysis scripts
│   ├── visualization.py      # Visualization scripts
└── README.md                 # Project documentation
```



### Visuals 

Graph of return of investment based on movie genre
![alt text](image.png)

Graph of number of movies released based on genre
![alt text](image-1.png)

Top six genres with the highest revenue by year
![alt text](image-2.png)

Top ten genres released including combinations
![alt text](image-3.png)

Graph showing voter rating distribution
![alt text](image-4.png)

Graph of voter rating distribution (excluding outliers)
![alt text](image-5.png)

Graph of top 10 movies by Bayesian average rating
![alt text](image-6.png)



### Results

- **Key factores to a movie success**: We identified critical factors that translates to movie success
- **Genre trends**: We identified the most popular genres and the least popular ones over the 10 years period.
- **Popular movies**: We identified a list of the top 10 most popular movies in the 10 years period.
- **Predictive Model**: Based on our analysis, we were able to predict the next blockbuster movie with an 92% accuracy 



### Contribution Guidelines
Contributions are welcome and appreciated! Please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Submit a pull request with a detailed explanation of your changes.



## Support information 

- Slack channel- p1_team6_rimi: [https://aipteastoctob-ypv8330.slack.com/archives/C084F6CUGUU]
- No expected assistance beyond Dec 19th 2024



### Contributors

- Jeff Oliver
- Leonard Forrester
- Steven Frasica
- Kevin Miller
- Dennis Bett
- Rakesh Rodda
- Rimi Sharma



### Acknowledgments

- Data source: [https://www.kaggle.com/datasets/asaniczka/tmdb-movies-dataset-2023-930k-movies]
- Pandas documentations: [https://pandas.pydata.org/pandas-docs/stable/index.html]
- Python documentation: [https://docs.python.org/3/]



### License information

This project is licensed under the MIT License.
































