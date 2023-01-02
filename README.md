# BeijingAirPollution
MODEL implementations

LSTM - LSTM.ipynb

Bi-LSTM - BiLSTM.ipynb

Transformers - Transformer.ipynb

Wide Transformers - WideTransformer.ipynb


LSTM Exclusion (excluded certain stations)
Used same LSTM.ipynb but excluded 4 mountainous stations

LSTM seasonal
Used same BiLSTM.ipynb but on seasonal data (PRSA_seasons)

Predictions on the test set are created in folder that contain *_pred_np

The *_AVG_pred.ipynb takes the predictions for the different models and averages on the 
same time scale.

The *_AirNow.ipynb computes the metrics on the airnow dataset
