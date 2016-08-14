# workshops

Workshops are based on the databricks EdX lectures on Apache Spark
Goal: Learn how to apply data science and data engineering techniques using parallel programming in Apache Spark. The workshops are heavily based on the databricks EdX Series.

Participants are expected to review the material before the session and complete the weekly challenges. Participants will be awarded up to 10 points per session based on their participation and labs completion. Questions during the session are encouraged, but priority will be given to questions send before the session and those that benefit the majority of the group.

#### late submissions

| Submission time| Points Substracted |
| ------------- |:-------------:|
| 1 week > submission > 2 weeks  | 1 |
| 2 week > submission > 3 weeks | 2 |
| 3 week > submission > 4 weeks | 3 |

How to communicate: use [#workshops channel of TAS Slack](https://torontoapachespark.slack.com/messages/workshops/).

** If you aren't a member; send an email to mehrdad@tranquant.com with _Slack Invitation Request_ as the subject

## View your profile and your points:
http://hackondata.com:9999/api/hackathon/profile?token=your-private_id  // find `your-private_id` in your Registration Confirmation E-mail

## Schedule:

The sessions will be delivered out by Google Hangout. Click on the session title to see the link to the youtube and hangout page for that session. All sessions will be recorded and published after the live session.

Every Thursday from 7:00pm to 8:30pm, starting on July 14, 2016 until the day of the hackathon.

### To Setup Your Environment:
Please follow the [instruction](https://goo.gl/sGzTZW)

### Sessions:

[All sessions are recorded and available for you to watch!](https://plus.google.com/u/1/collection/UUr_aB)

#### [Jul 14 - Virtual session - Intro](sessions/exercise_1.md)
- Notebook usage
- Intro to spark and pySpark API
- Using RDDs
- Lambda functions
- RDD actions, transformation, caching
- Debugging and lazy evaluation

#### [Jul 21 - Virtual session - RDDs](sessions/exercise_2.md)
- Create a RDD and pair RDD
- Counting words
- Finding unique words and mean value
- Reference to regular expressions https://regex101.com/#python
- Apply word count to a file

#### [Jul 28 - Virtual session  - Data Exploration](sessions/exercise_3.md)
- Server log analysis statistics
- Finding problematic endpoints, unique hosts
- Visualizing data analysis results
- Data exploration

#### [Aug  4 - In-person part I - Text Analysis](sessions/exercise_4.md)
- Text similarity of Entity Resolution
- Weighted bag-of-words
- Cosine similarity
- Scalable Entity Resolution
- Analysis

#### [Aug 11 - Virtual session: Review](sessions/exercise_5.md)
- Math review
- Numpy and spark
- Lambda functions

#### [Aug 18 - Virtual session  - Read, parse, and visualize dataset](sessions/exercise_6.md)
- Baseline model
- Train linear regression
- Hyperparameter tuning
- Features interaction

#### Aug 25 - Virtual session - Feature Hashing
- One-hot-encoding
- OHE Dictionary
- Prediction and log loss evaluation
- Feature reduction

#### Sep  1 - In-person part II - Principal Component Analysis 
- PCA on a sample dataset
- PCA calculation and evaluation
- Data preprocessing for PCA
- Feature-based aggregation

#### Sep  9 - Hackathon day

Additional information:
- Welcome to databricks:
https://docs.cloud.databricks.com/docs/latest/databricks_guide/index.html#00%20Welcome%20to%20Databricks.html
- Databricks dbfs
https://docs.cloud.databricks.com/docs/latest/databricks_guide/01%20Databricks%20Overview/10%20Databricks%20File%20System%20-%20DBFS.html
- Mount s3 bucket to databricks:
https://docs.cloud.databricks.com/docs/latest/databricks_guide/index.html#03%20Data%20Sources/2%20AWS%20S3%20-%20py.html
