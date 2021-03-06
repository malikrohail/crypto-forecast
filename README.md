# crypto-forecast

Link: https://www.youtube.com/watch?v=UrQdV2LW-a0

This model enables you to predict on the future value of any cryptocurrency (available on Coinmarketcap.com), for any number of days into the future! The application is built with Streamlit (the front-end) and the Facebook Prophet model, which is an advanced open-source forecasting model built by Facebook, running under the hood. You can select to train the model on either all available data or a pre-set date range. Finally, you can plot the prediction results on both a normal and log scale.

# Libraries Used
# a. Cryptocmd
Cryptocmd is a very useful open source for the retrieval of crypto coin
datasets based on https://coinmarketcap.com/

# b. Plotly
Plotly allows users to import, copy and paste, or stream data to be analyzed and visualized. For analysis and styling graphs, Plotly offers a Python sandbox (NumPy supported), Datagrid, and GUI. Python scripts can be saved, shared, and collaboratively edited in Plotly.

# c. Fbprophet
Fbprophet is an open-source that we use to create a model to predict
the price of a crypto coin because the model is fast in the computational
process and easy to use.

# d. Streamlit
Streamlit is an open-source python framework for building web apps for Machine Learning and Data Science. We can instantly develop web apps and deploy them easily using Streamlit. Streamlit allows you to write an app the same way you write a python code. Streamlit makes it seamless to work on the interactive loop of coding and viewing results in the web app.



# Result
The results so far are somewhat promising. The validation accuracy of the network is just above 70 after adding a couple more indicators and ensuring an equal amount of training labels. This can be helpful in market analysis but cannot be used for automated trading due to false positives and network error. Adding features and have better training data should improve the model but it can get really difficult because global news plays a pivotal factor in terms of crypto market pricing so it really gets difficult to be accurate most of the time.

# References
1. https://awesomeopensource.com/project/guptarohit/cryptoCMD
2. https://plotly.com/python/text-and-annotations/
3. https://streamlit.io/
4. https://facebook.github.io/prophet/

