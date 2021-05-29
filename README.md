# Stock Price Predicition with LSTM

Stock Price Prediction using LSTM Algorithm. This prediction model build based on the historical stock price data. For example, the 60-day historical as an input used to predict the price at 61st day. The model built with Keras with Dense and LSTM as its neuron layers.

V2 Changes:
- Use Keras Functional API for the model.
- Logged return variable added for training model.
- Retuning the model because new variable added.
- Add Bidirectional wrapper for LSTM.

Reference:
- LSTM layer https://keras.io/api/layers/recurrent_layers/lstm/
- Stock Price Prediction Using Python & Machine Learning https://youtu.be/QIUxPv5PJOY
- Stock Price Prediction Project with TensorFlow Keras https://youtu.be/dKBKNOn3gCE
- Why Log Returns https://quantivity.wordpress.com/2011/02/21/why-log-returns/
- Bidirectional layer https://keras.io/api/layers/recurrent_layers/bidirectional/
