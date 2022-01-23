# int20H_2022_testove

First EDA 
Find 12 drivers with all nan and always target 0
Another corelation with target
But nothing for new Features or changing old

NN for table date without PP ( normalization ) give 0.92 on CV

Mean give better score than median


Then LGBM + XGB 
One driver - 4 rows -> mean of all 4 weeks
CV 0.958 PB 0.96

In last 1 hour find that 
Create DF 1 driver 1 rows with columns from 4 weeks give better result
Only XGM model give CV 0.97686 and PB 0.97839

Improvements:
Run LGBM and NN models on dataset
