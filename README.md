# Customer Analytics: Preparing Data for Modeling
Apply your knowledge of data types and categorical data to prepare a big dataset for modeling!

You've been hired by a major online data science training provider to store their data much more efficiently, so they can create a model that predicts if course enrollees are looking for a job. You'll convert data types, create ordered categories, and filter ordered categorical data so the data is ready for modeling. You'll use the dataset `customer_train.csv` to create a DataFrame called `ds_jobs_transformed` that meets the following criteria:
- Columns containing categories with only two factors must be stored as Booleans (`bool`).
- Columns containing integers only must be stored as 32-bit integers (`int32`).
- Columns containing floats must be stored as 16-bit floats (`float16`).
- Columns containing nominal categorical data must be stored as the `category` data type.
- Columns containing ordinal categorical data must be stored as ordered categories, and not mapped to numerical values, with an order that reflects the natural order of the column.
- The DataFrame should be filtered to only contain students with 10 or more years of experience at companies with at least 1000 employees, as their recruiter base is suited to more experienced professionals at enterprise companies.

Executed on 11-12Jul25

[Link](https://app.datacamp.com/learn/projects/customer_analytics_preparing_data_for_modeling/guided/Python) to project on DataCamp
