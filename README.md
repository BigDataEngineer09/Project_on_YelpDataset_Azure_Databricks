# Project_on_YelpDataset_Azure_Databricks

1. Conducted data ingestion by reading Yelp datasets from Azure Data Lake Storage (ADLS) and optimized the data format by converting JSON to Parquet for enhanced performance.

2. Profiled the datasets to determine the total number of records in each.

3. Implemented data partitioning based on a date column for efficient storage and query performance.

4. Explored and compared the use of `repartition()` and `coalesce()` for optimal data distribution.

5. Conducted user analysis by identifying the top 3 users based on their total number of reviews and determining the top 10 users with the most fans.

6. Analyzed the top 10 categories by the number of reviews.

7. Explored businesses with over 1000 reviews and analyzed the number of restaurants per state.

8. Conducted state-wise restaurant analysis by identifying the top 3 restaurants in each state and listing the top restaurants in a state based on the number of reviews.

9. Determined the number of restaurants in Arizona state per city.

10. Executed a broadcast join to analyze restaurants based on review ratings in Phoenix city.

11. Identified the most rated Italian restaurant in Phoenix.

Source: Project from ProjectPro:- https://www.projectpro.io/project-use-case/analyze-yelp-data-spark-parquet-project
