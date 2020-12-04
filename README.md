# MSBD5001_Kaggle_HW
- Kaggle (Playgournd): https://www.kaggle.com/hkustcenz/msbd5001-kaggle
- Kaggle (ARIMA): https://www.kaggle.com/hkustcenz/kaggle-final

# Notebook Explaination
- Kaggle (Playgournd): https://www.kaggle.com/hkustcenz/msbd5001-kaggle
- This includes some utility like visualizing data, extracting holiday and some code testing.
---
- Kaggle (ARIMA): https://www.kaggle.com/hkustcenz/kaggle-final
- Finally I decide to use ARIMA model, which is time-series forcasting model, I think this will outperform other model like neural network.

# Package used
https://www.statsmodels.org/stable/index.html
```
import statsmodel
statsmodel.__version__
```
Check the version of statsmodel. When you broswe online, you can see different code style, which makes you confused. There is some major different on some code. Check it carefully.
# Reproduce the result
- Jupyter: 
    - Train.ipynb, will generate a file predictions containing all data from 2018-01-01-01:00 to 2018-12-31-23:00
    - submit.ipynb, will transform predictions.csv to test_submit.csv which is the file to submit.
- Kaggle:
    - Kaggle (ARIMA): https://www.kaggle.com/hkustcenz/kaggle-final
    - Will output a test_submit.csv
