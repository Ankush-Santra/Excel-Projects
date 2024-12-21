<div align="center">
  <img src="Images/Salary Data.png" alt="Salary Data" width="600"/>
  <p><em>A Glimpse of the Salary Dataset</em></p>
</div>

## Data Source

**Shoutout to Luke Barousse's dataset** - [Data Analyst Job Postings on Kaggle][1]

### About the Dataset
This dataset pulls job postings from Google's search results for Data Analyst positions in the United States. Data collection started on **November 4th, 2022**, and approximately **100 new job postings** are added to this dataset daily.

### How I Used the Dataset
I utilized two different methods to fetch and process this dataset for my dashboards:

1. **Manual Download and Transformation**  
   For the first dashboard, I manually downloaded the dataset from Kaggle and transformed it using **Power Query** in Excel.
  
2. **Live API Integration and Transformation**  
   For the second dashboard, I implemented a live [API][2] connection to fetch the dataset automatically. This approach ensures that new changes and updates to the dataset are fetched dynamically. The fetched data was then transformed using **Power Query** for analysis.
   

[1]: https://www.kaggle.com/datasets/lukebarousse/data-analyst-job-postings-google-search
[2]: https://storage.googleapis.com/gsearch_share/gsearch_jobs.csv
