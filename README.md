# stock-market-prediction
Stock Trend Prediction Machine Learning Model in Python using the LSTM(Long Short-Term Memory)

The **Long Short-Term Memory (LSTM)** is a type of recurrent neural network (RNN) that excels at capturing long-term dependencies in sequential data. Unlike traditional RNNs, LSTM cells are designed to store and control information over longer time intervals, making them particularly effective for tasks involving sequential data where order and context matter significantly.

In the context of sequence prediction problems, such as stock price forecasting, LSTM's ability to retain past information becomes a valuable asset. The prediction of future stock prices indeed heavily relies on historical prices and patterns in the stock market. **LSTM's architecture allows it to maintain a memory of past price movements and capture complex relationships among different time steps, enabling better predictions.**

The basic structure of an LSTM cell consists of three essential components: **the input gate, the forget gate, and the output gate.** These gates regulate the flow of information within the cell, ensuring relevant information is retained and irrelevant information is discarded. This gating mechanism helps the LSTM model in mitigating the vanishing and exploding gradient problems that often occur in traditional RNNs, making it more effective in capturing long-range dependencies.

Overall, LSTM's ability to learn order dependence and retain past information in sequences has made it a popular choice for sequential data analysis, including applications in predicting stock prices due to its capability to effectively capture the temporal dynamics in financial markets. 

I have used 70% of 12 years of data from Yahoo Finance's open source to train the model and the other 30% to test the model.

**Future Plans:** 
I intend to convert this model into a web application. 
