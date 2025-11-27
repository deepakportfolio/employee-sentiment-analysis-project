# Employee Sentiment Analysis
This project applies Natural Language Processing (NLP) and Machine Learning (ML) to employee communication data (test.csv) to uncover sentiment trends, engagement levels, and potential flight risks. By combining statistical analysis with predictive modeling, it demonstrates how text analytics can support HR decision‑making.

 # Objectives
 ## Sentiment Labeling → #### Classify each message as Positive, Negative, or Neutral

 ## Exploratory Data Analysis (EDA) → Visualize sentiment distribution, trends, and anomalies

 ## Employee Score Calculation → Compute monthly sentiment scores per employee

 ## Employee Ranking → Identify top 3 positive and negative employees each month

 ## Flight Risk Detection → Flag employees with ≥4 negative messages in a rolling 30‑day window

 ## Predictive Modeling → Build regression models to forecast sentiment behavior

🧩 Dataset
File: test.csv

Content: Employee messages (subject, body, from, date)

Processed Features:

combined_text → Subject + body combined

Sentiment → Labeled sentiment category

Score → Numeric sentiment score (+1, -1, 0)

Month → Extracted from timestamps

⚙️ Tools & Libraries
Category	Libraries
Data Handling	pandas, numpy
NLP	nltk (VADER), transformers (optional)
Visualization	matplotlib, seaborn
ML Modeling	scikit‑learn (Linear Regression)
Environment	Jupyter Notebook
Model Metrics

📐 R² Score: ~0.57 (moderate predictive power)

📉 RMSE: Moderate

📊 MAE: Acceptable range

🔑 Key Insights
Most messages were neutral, with pockets of consistent negativity.

Certain employees showed declining engagement over time.

Flight risk employees had multiple negative interactions in short periods.

Regression modeling provided moderate predictive accuracy for sentiment trends.

🏁 Conclusion
This project demonstrates how NLP + ML can transform raw communication data into actionable insights. It highlights opportunities for organizations to:

Monitor morale and engagement

Identify disengaged employees early

Predict potential retention risks

Support HR with data‑driven strategies

👤 Author
Deepak 📌 Submission Title: AI Project Submission — Employee Sentiment Analysis
