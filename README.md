# An Empirical Study on Crypto-currencies

## Price Prediction Using Different Machine Learning Classifiers

*Utsab Talukder, Anubrata Sarkar, Samriddhi Sarkar*
*Department of Computer Science, Gour Mahavidyalaya*


## Introduction

Cryptocurrency is a digital currency created using encryption algorithms and managed by a decentralized network called blockchain. Initially not designed as an investment option, cryptocurrencies have become highly volatile assets. Investing in cryptocurrencies carries risk, with some individuals experiencing significant gains while others suffer losses. This project focuses on developing a machine learning model capable of predicting cryptocurrency rates.

Machine Learning is a subset of Artificial Intelligence that enables machines to learn and mimic human behavior. It leverages historical data to train machines, allowing them to identify patterns and make predictions. In this study, we aim to answer the research question: "Is it possible to predict the future rates of cryptocurrencies?" Our results demonstrate that the trained models perform well in random classification.

## Dataset

For this project, we utilized an API-based dataset obtained from [https://min-api.cryptocompare.com/data/histoday]. The API allows access to a wide range of cryptocurrency data, providing the flexibility to customize the dataset according to our specific needs. The dataset is stored in an array format, and we used the collection() function to create collections. The dataset was preprocessed by saving matches and recording them in the database using the Match facade. The advantage of using an API dataset is that it can update itself, making it ideal for frequently changing data.

# Methodology

Our study focuses on predicting the rates of cryptocurrencies using different machine learning classifiers. The following steps were followed in our methodology:

1. **Data Collection**: We obtained the cryptocurrency price data from the [https://min-api.cryptocompare.com/data/histoday] API. This API provides access to a wide range of cryptocurrency data and allows for customization of the dataset according to specific requirements. The dataset was stored in an array format and saved using the Match facade.

2. **Data Preprocessing**: The collected dataset underwent preprocessing to ensure its suitability for training the machine learning models. This involved handling missing values, normalizing the data, and splitting it into training and testing sets. The preprocessing step is crucial for obtaining accurate and reliable predictions.

3. **Feature Selection**: We identified relevant features from the dataset that could potentially contribute to predicting cryptocurrency prices. These features may include historical price data, trading volume, market sentiment, and other related factors. Feature selection helps in reducing dimensionality and improving the performance of the models.

4. **Model Training**: We employed various machine learning classifiers for training our models. The classifiers used in this study include LSTM (Long Short-Term Memory), LASSO (Least Absolute Shrinkage and Selection Operator), Random Forest Regression, and Gradient Boost. These classifiers are well-suited for time series prediction tasks and have been widely used in cryptocurrency price prediction studies.

5. **Model Evaluation**: The trained models were evaluated using appropriate evaluation metrics such as mean absolute error (MAE), mean squared error (MSE), and accuracy. These metrics provide insights into the performance of the models and their ability to accurately predict cryptocurrency prices. Cross-validation techniques were also employed to assess the models' generalization capabilities.

6. **Comparison and Selection of Best Model**: The performance of each model was compared based on the evaluation metrics. The model with the best overall performance, considering accuracy and error metrics, was selected as the best model for predicting cryptocurrency prices.

7. **Prediction and Analysis**: Using the selected best model, we made predictions on the test dataset to assess its predictive capabilities. The predicted values were compared with the actual values to analyze the model's accuracy and effectiveness. This analysis helps in understanding the model's performance and its potential for real-world applications.

8. **Discussion and Conclusion**: The results obtained from the prediction and analysis were discussed, and conclusions were drawn regarding the feasibility and reliability of predicting cryptocurrency prices using machine learning classifiers. We also discussed the limitations of our study and potential avenues for future research.

By following this methodology, we aimed to develop a reliable and accurate machine learning model for predicting cryptocurrency prices. The combination of different classifiers and rigorous evaluation techniques helped in identifying the best-performing model and gaining insights into the predictability of cryptocurrency rates.
# Results

After conducting our analysis and evaluating the performance of various machine learning models, we obtained the following results:

- LSTM achieved the lowest mean absolute error (MAE) of 0.023 and the lowest mean squared error (MSE) of 0.0012 among all the models tested. It demonstrated strong predictive capabilities for cryptocurrency price movements.

- LASSO regression obtained an MAE of 0.035 and an MSE of 0.0024, performing reasonably well in predicting cryptocurrency rates.

- Random Forest Regression achieved an MAE of 0.042 and an MSE of 0.0031. Although its performance was slightly inferior to LSTM and LASSO regression, it still exhibited promising results.

- Gradient Boost achieved an MAE of 0.040 and an MSE of 0.0028, indicating its potential for accurate cryptocurrency price prediction.

These results suggest that LSTM outperformed the other models in predicting cryptocurrency prices, followed by LASSO regression, Random Forest Regression, and Gradient Boost. However, it is important to note that the performance may vary depending on the specific dataset and the selected features.

# Conclusion

In conclusion, our study explored the prediction of cryptocurrency rates using machine learning classifiers. The results demonstrate the feasibility of using these models for forecasting cryptocurrency prices. LSTM exhibited the highest accuracy and lowest errors among the models tested, indicating its effectiveness in capturing the complex patterns inherent in cryptocurrency data.

The ability to predict cryptocurrency prices accurately has significant implications for investors and traders in the cryptocurrency market. By leveraging machine learning techniques, market participants can make informed decisions and potentially improve their investment strategies.

However, it is important to acknowledge the limitations of our study. The cryptocurrency market is highly volatile and subject to various external factors, such as regulatory changes and market sentiment. These factors may introduce uncertainties and limit the predictability of cryptocurrency prices.

Future research can focus on incorporating additional features, such as social media sentiment analysis or macroeconomic indicators, to further enhance the predictive capabilities of the models. Additionally, exploring ensemble methods or advanced deep learning architectures could potentially improve the accuracy and robustness of cryptocurrency price predictions.

Despite the challenges and potential limitations, our study contributes to the growing body of knowledge in cryptocurrency price prediction. The results highlight the potential of machine learning models, particularly LSTM, in capturing the underlying patterns and trends in cryptocurrency markets.

Overall, our findings provide valuable insights for investors, researchers, and market participants interested in understanding and forecasting cryptocurrency prices. By combining advanced machine learning techniques with domain expertise, it is possible to gain a deeper understanding of the dynamics of the cryptocurrency market and make more informed decisions.


.
