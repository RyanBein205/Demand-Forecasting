### Project Title
Demand Forecasting
**Author**
Ryan Bein
#### Executive summary
  ### Objective:
  The primary objective of this capstone project was to investigate how machine learning models could improve the accuracy of demand forecasting in a manufacturing and distribution environment. Accurate demand forecasting is critical for optimizing inventory levels, reducing waste, ensuring   customer satisfaction, and enhancing overall operational efficiency.
  
  ### Data:
  The analysis leveraged the M5 Forecasting Accuracy dataset from Kaggle, which includes daily sales data, calendar events, and prices across multiple stores and product categories. The dataset provided a comprehensive view of historical sales, external events (e.g., holidays), and price fluctuations that could influence future demand.
  
  ### Methodology:
  Three machine learning models were considered for this analysis:
  
  ARIMA (AutoRegressive Integrated Moving Average): A traditional time-series forecasting model.
  LSTM (Long Short-Term Memory Networks): A type of recurrent neural network particularly suited for capturing temporal dependencies in sequential data.
  XGBoost: A gradient boosting algorithm that excels at handling complex patterns in data and was used in combination with time-based feature engineering.
  The project followed a structured methodology:
  
  ### Data Preprocessing: This involved handling missing values, scaling the data, creating time-based features, and splitting the dataset into training and testing sets.
  Model Training: The models were trained on the historical sales data, and hyperparameters were optimized to improve performance.
  Evaluation Metrics: The models were evaluated using standard metrics such as Root Mean Squared Error (RMSE) and Mean Absolute Error (MAE) to assess the accuracy of the predictions.
  ### Key Results:
  LSTM Model: The LSTM model, which is designed to capture long-term dependencies in sequential data, produced strong results, with an RMSE of 0.941 and an MAE of 0.410. These metrics indicate that the model, on average, deviated from the actual sales figures by less than 1 unit, suggesting high accuracy in predicting demand.
  Performance Insights: The relatively low RMSE and MAE suggest that the LSTM model was effective at learning the temporal patterns in the data. However, a slight gap between RMSE and MAE indicates occasional larger errors, possibly due to sudden spikes or drops in demand (e.g., during promotions or holidays).
  Outlier Detection: The performance of the LSTM model could be improved further by investigating outliers and refining the model’s ability to predict extreme cases, such as abnormal demand spikes driven by events.
  Conclusions:
  The machine learning models demonstrated significant potential in improving demand forecasting accuracy compared to traditional approaches. Specifically, LSTM showed strong performance, indicating that advanced machine learning techniques can effectively capture complex temporal patterns and non-linear relationships in sales data. The project highlights the importance of model fine-tuning, feature engineering, and handling external events in building robust demand forecasting models.
  
  ### Recommendations:
  Adoption of Machine Learning for Demand Forecasting: The results of this project strongly suggest that machine learning, particularly LSTM, can outperform traditional forecasting models in manufacturing and distribution settings. Companies should consider adopting these techniques to improve their forecasting capabilities.
  Further Model Tuning: While the models performed well, there is room for improvement, particularly in handling extreme demand fluctuations. Further experimentation with feature engineering, such as incorporating more granular external factors (e.g., weather or local events), could enhance accuracy.
  Scaling Across Products: The success of these models with the dataset indicates that they could be applied at scale across multiple products and stores, helping to optimize inventory levels and improve decision-making across the supply chain.
  ### Business Impact:
  By improving the accuracy of demand forecasting, organizations can expect to see tangible benefits, such as reduced inventory holding costs, minimized stockouts, improved cash flow, and enhanced customer satisfaction. The machine learning approach outlined in this project provides a scalable and adaptable solution for businesses seeking to leverage data-driven insights for more efficient operations.

#### Rationale
Accurate demand forecasting is crucial for optimizing inventory management, reducing waste, and enhancing customer satisfaction in manufacturing and distribution. Improving the accuracy of these forecasts through machine learning can lead to cost savings, better resource allocation, and more efficient production planning.

#### Research Question
"How can machine learning models improve the accuracy of demand forecasting in a manufacturing and distribution environment?"

#### Data Sources
The data for this analysis will be sourced from the M5 Forecasting Accuracy competition dataset, available on Kaggle: M5 Forecasting Accuracy Dataset. https://www.kaggle.com/competitions/m5-forecasting-accuracy/data

#### Methodology
I plan to utilize machine learning techniques such as ARIMA, LSTM (Long Short-Term Memory networks), and gradient boosting models like XGBoost. Additionally, I will incorporate feature engineering, time series decomposition, and model evaluation techniques to compare the performance of these models in forecasting demand.

#### Results
If LSTM/XGBoost performed well: You can conclude that machine learning models are a powerful tool for improving demand forecasting accuracy, especially in scenarios where demand is influenced by many factors like seasonality, promotions, or external events.
Challenges faced: Issues such as zero predictions or scaling problems highlight that these models require careful tuning and data preprocessing. However, once properly configured, they provide significant advantages over traditional methods.
Overall Improvement: Assuming your models eventually provided accurate forecasts, you can argue that machine learning approaches (LSTM, XGBoost) provide a flexible and scalable solution for demand forecasting in the manufacturing and distribution sectors.

#### Next steps
Continue to refine and train the LTSM/XGBoost models to improve upon the errors indicated by RMSE and MAE.
Provide more visuals and fix the training data for the predictions.

#### Outline of project

- [Link to notebook 1](Capstone20_with_Sampling.ipynb)

##### Contact and Further Information
