# Big Data & NoSQL Databases, Spring 2024

---

## Project: Kickstarter Crowdfunding Analysis

### Overview:
In this project, you will analyze a dataset sourced from Kickstarter, focusing on predicting and enhancing the success of crowdfunding campaigns. Kickstarter is an online platform where entrepreneurs pitch their projects to obtain funding from the public.

### Dataset Description:
The dataset includes detailed information about various crowdfunding projects:
- **ID:** Unique Kickstarter ID
- **name:** Name of the proposal
- **category:** Specific category of the project
- **main_category:** Parent category of the project
- **currency:** Original currency of the goal
- **deadline:** Project expiry date
- **goal:** Funding goal in the respective currency
- **launched:** Project launch date
- **pledged:** Amount pledged before the deadline
- **state:** Current state of the project (e.g., success, fail)
- **backers:** Number of backers
- **country:** Country of the project
- **usd_pledged:** Pledged amount converted to USD (by Kickstarter)
- **usd_pledged_real:** Pledged amount converted to USD (by Fixer.io)
- **usd_goal_real:** Goal amount converted to USD (by Fixer.io)

### Tasks:
1. **Data Cleaning and Engineering:**
   - Handle missing values, duplicates, and perform necessary transformations.

2. **Querying and Visualizations:**
   - Implement 3 queries using Spark (SQL or DataFrames), Cassandra, or MongoDB.
   - Create 3 visualizations based on the query results to provide insights into the dataset.

3. **Machine Learning with SparkML:**
   - Prepare data for machine learning by combining feature columns into a single vector column.
   - Build at least 3 models to predict the success of crowdfunding projects using SparkML.
   - Define project success by converting the "state" column into a binary outcome: 1 for successful projects and 0 for others (excluding live projects).

For further details and dataset specifics, refer to the project folder provided.
