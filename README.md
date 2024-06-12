# NeuralProphetStarterNotebook

**Who is this for?**

This notebook is for people who are new to data science and want a simple notebook they can execute when they see a dataset looking for stock market predictions. This way you can learn and use this as a starting block for time-series problems asking for a future prediction.

Stock market predictions are a time-series forecasting problem that can be solved with regression models. A model that I've been using with some success for this task is Neural Prophet.

**What is Neural Prophet?**

*NeuralProphet, an open-source time series forecasting tool built on PyTorch, offers a robust approach to predicting future stock prices. By integrating core features from Facebook's Prophet and deep learning capabilities, NeuralProphet enhances forecast accuracy through its hybrid model. It leverages autoregressive models, seasonality, and holiday effects, and incorporates neural network elements to capture complex patterns in stock price movements. This combination allows it to effectively handle non-linearities and intricate temporal dependencies present in financial data. Consequently, traders and analysts can use NeuralProphet to generate more reliable and precise forecasts for stocks, aiding in informed decision-making and strategic planning.*

**Instructions**

Inside you'll find a code block that can make a prediction on stock data with the features "Date, Open, High, Low, Close, Adj Close, Volume" which is very common. I've added comments, look for the spots where you have to change the variable. In this problem format you will adjust the number of steps that you want the model to predict for. 

The default frequency for this data is days, but you could change the frequency yourself and predict for months or years etc. Keep in mind to optimize the predictions you will need to adjust the hyperparameters of the Neural Prophet model, so please just use this as a starting block.

You can optionally run the subsequent code blocks one-by-one to get an idea of what the code does. I've added headers to explain each step.
