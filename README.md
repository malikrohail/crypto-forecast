# crypto-forecast

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






Workflow overview from the user side:
1. User will input/enter a keyword
2. Visualization of profits is made on the landing page
3. Based on the model created, a visualization of the prediction results of the model will be
displayed.
Workflow from me as a developer:
1) I will create a website landing page design (1 page) containing an input form &
visualization of profits data.
2) Research for dynamic data retrieval methods (users can input various data)
3) Start collecting datasets & testing whether the method is dynamic or not
4) based on the diverse data, research which deep learning model is most suitable for
dynamic data. Improvising website design to make it more user friendly.
5) website/local host functionality testing 
