# codtech_tasks

TASK 1: Big Data Analysis

Tool: PySpark 


Objective: To demonstrate scalability by performing analysis on a dataset.


Methodology: The code initializes a SparkSession to move the data into a distributed environment. It performs aggregation (groupBy and agg) to calculate the Average Star Rating and Review Count per product.


Deliverable: A notebook section with the PySpark code and the resulting aggregated insights.

TASK 2: Predictive Analysis Using Machine Learning
Tool: Scikit-learn (Logistic Regression)


Objective: To build a Machine Learning model (classification) to predict outcomes based on the dataset.

Methodology: The textual review data is converted into numerical features using TF-IDF Vectorization. A Logistic Regression classifier is then trained and evaluated to predict the binary score (Positive/Negative).


Deliverable: A notebook section demonstrating feature selection, model training, and evaluation via the Classification Report.

TASK 3: Dashboard Development

Tool: Dash and Plotly 


Objective: To create an interactive dashboard to visualize the dataset.

Methodology: A multi-chart dashboard was built using Dash, with an optimized layout. It displays: Sentiment Distribution (from Task 4), Rating Trend Over Time, and a detailed Sentiment Breakdown Per Product (Actionable Insight).


Deliverable: A fully functional dashboard with actionable insights.

<img width="500" height="350" alt="newplot" src="https://github.com/user-attachments/assets/f5cbb53a-566e-4149-9187-21bccd1540f7" />
<img width="500" height="350" alt="newplot (1)" src="https://github.com/user-attachments/assets/c5dc6ae1-237b-444f-b8a2-b89e59038bd6" />
<img width="500" height="350" alt="newplot (2)" src="https://github.com/user-attachments/assets/773b02a7-0996-4abf-a48f-18656c5845ce" />
<img width="500" height="350" alt="newplot (3)" src="https://github.com/user-attachments/assets/66a0d303-2a69-4865-a203-288631c61aaf" />




TASK 4: Sentiment Analysis

Tool: NLTK VADER (Natural Language Processing) 


Objective: To perform sentiment analysis on textual data (reviews).

Methodology: The VADER lexicon model was applied to categorize the review text into the categorical feature Predicted_Sentiment (Positive, Negative, or Neutral).


Deliverable: A notebook section showcasing data preprocessing, model implementation (VADER), and insights (Sentiment Distribution and Word Cloud).

Instructions for Reviewer
Open the Notebook: Open the submitted .ipynb file in Google Colab.

