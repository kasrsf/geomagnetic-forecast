# Model Description

* Single layer of LSTM with 512 neurons
  
* Trained for 20 epochs on batches of size 32 with 32 timesteps of data each

## Features

* Hourly solar wind data aggregated by day. The mean and standard deviation of the features are fed to the model.

* Features used:
  * bt
  * temperature
  * bx_gse
  * by_gse
  * bz_gse
  * speed
  * density
  * smoothed_ssn


  