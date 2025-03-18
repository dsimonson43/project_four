# Project Proposal

## Predicting Housing Prices: Minnesota vs US National

* **Objectives**
  * Analyze and compare Minnesota and national housing price data from 2012–2025.
  * Build a predictive model to forecast housing prices 5–10 years into the future.
    * Is it possible to build an effective model to predict future home prices?
  * Visualize trends and affordability metrics over time.

## Data Source

[Redfin data center](https://www.redfin.com/news/data-center/) 

* Download the State `state_market_tracker.tsv000` and National `us_national_market_tracker.tsv000`.
* Review the past 10 plus years of data and garner insights and trends based on available data.

## Methodolgy

* Data Cleaning - Use pandas to preprocess the datasets in jupyter notebook.
* Storage - Use PostgreSQL database for structured storage.
* Analysis - Compare Minnesota vs US National data trends.
* Model Development:
  * Build a predictive model using TensorFlow and Keras to forecast future housing prices/values.
  * Train and validate the model using our 2 datasets, ie. train_test_split etc.
* Scoring the model:
  * Accuracy, precision, recall, confusion matrix
  * Root Mean Squared Error (RMSE)
* Visualizations - Matplotlib, Plotly, Tableau, etc.

## Deliverables

* Cleaned dataset stored in PostgreSQL
* Predictive model for housing prices with benchmark years, example (5, 10, 20).
* Visualizations comparing trends and predictions
* Final slide presentation summarizing our findings and displaying the visualizations.

## Team Members

* Chad Hillman
* Mahamoud Jama
* DJ Dimetros
* Daniel Simonson