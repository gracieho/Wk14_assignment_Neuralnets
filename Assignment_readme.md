Week 14 Homework Assignment - Deep Neural Networks

In the Week 14 Neural Network assignment we compared the outcome of using two different datasets on the same deep neural net model.
One more used the Fear and Greed index and the second model used recent closing prices, both to predict the future price of Bitcoin prices.

Various options were tested around window size of the number of days data to be used as inputs, the batch size and epoch size used in the neural network model.  (The results of this are documented in the 'istm_stock_predictor_fng.ipynb' file.) 
An optimal selection was found using a 5 day window, batch size of 30, and epochs of 25.  This appeared to produce the lowest loss outcome for the model.

Overall, the model loss for the future price predictions using the Fear and Greed index was 0.0937, while the loss of the predictive model using Closing Price was 0.0043.  That is, the model using Closing Prices was a much better predictor of actual price.

A visual examination of graphs showing predicted vs actual price, clearly shows that the Closing Price model predictions tracked more closely to the actual prices than the Fear and Greed model.

