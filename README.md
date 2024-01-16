# BeijingAirPollution
Read our paper for more in depth information:
[Beijing Air Pollution Time Series Modeling](Paper/Predicting_Air_Pollution_Beijing_Deep_Learning.pdf) 

This was a group project to use time series model to predict the air pollution (PM2.5)
in Beijing China. We utilized various deep learning models to predict PM2.5 data using an input of
48 hours to predict ahead 6 hours and 24 hours of PM2.5 levels. You can find the implementations 
of the models below 

[LSTM](LSTM.ipynb) 
</br>
[Bi-LSTM](BiLSTM.ipynb)  
</br>
[Transformers](Transformer.ipynb)  
</br>
[Wide Transformers](WideTransformer.ipynb)  

There are multiple stations that reported PM2.5 which we excluded some moutainous stations.

![image](https://github.com/hwangdav000/Beijing_Air_Pollution/assets/29682356/1f572e65-d9f2-4722-a7b1-94167e4ebfaa)

We also created  separate seasonal models to account for the variation in seasonality and also had a baseline
to assess our models against.

Results

![image](https://github.com/hwangdav000/Beijing_Air_Pollution/assets/29682356/45b6b22f-6fe6-4ae8-ba87-ac705571c9aa)

March to August PM2.5 prediction on all models (2016)

![image](https://github.com/hwangdav000/Beijing_Air_Pollution/assets/29682356/571eb102-ed56-4cc3-8552-0d94b982457b)

We found that we got better results when predicting only 6 hours ahead and that Bidirectional LSTM model performed the best
followed by LSTM and then the Transformer models. All the models outperformed the baseline.

