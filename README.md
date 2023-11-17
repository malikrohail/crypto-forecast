# Crypto-Forecast

## Overview
The Crypto-Forecast application is designed to predict the future value of any cryptocurrency listed on [Coinmarketcap.com](https://coinmarketcap.com/). It utilizes Streamlit for the front-end interface, and the Facebook Prophet model for robust forecasting capabilities. This advanced model was developed by Facebook and is known for its efficiency and ease of use.

[Watch Demo Video](https://www.youtube.com/watch?v=UrQdV2LW-a0)

Users can train the model on all available data or limit the training to a specific date range. Predictions can be displayed on standard or logarithmic scales to accommodate different analysis needs.

## Libraries Used

### Cryptocmd
Cryptocmd facilitates the retrieval of cryptocurrency datasets, leveraging data from [Coinmarketcap](https://coinmarketcap.com/). It's an essential tool for accessing historical crypto coin data.

### Plotly
Plotly is a versatile library that supports data importation and visualization. It provides a Python environment for data analysis, a Datagrid for data manipulation, and a GUI for graph styling. Plotly's collaborative platform allows for the sharing and editing of Python scripts.

### Fbprophet
Fbprophet, developed by Facebook, is utilized for its rapid computational capabilities and user-friendly interface. It's the core of our predictive model, helping to forecast crypto coin prices effectively.

### Streamlit
Streamlit is a powerful framework for building web applications tailored to Machine Learning and Data Science. It simplifies the deployment process and offers a seamless coding experience. Coding and viewing the results are as straightforward as writing regular Python scripts.

## Result
The model's validation accuracy has reached just above 70% after fine-tuning with additional indicators and balancing training labels. While the results are promising for market analysis, they are not yet reliable for automated trading due to the potential for false positives and network errors. Enhancing the model with more features and better training data may lead to improvements. However, predicting the volatile crypto market remains challenging due to the significant impact of global news on pricing.

## References
1. [CryptoCMD on Awesome Open Source](https://awesomeopensource.com/project/guptarohit/cryptoCMD)
2. [Plotly Text & Annotations](https://plotly.com/python/text-and-annotations/)
3. [Streamlit Official Site](https://streamlit.io/)
4. [Facebook Prophet Documentation](https://facebook.github.io/prophet/)
