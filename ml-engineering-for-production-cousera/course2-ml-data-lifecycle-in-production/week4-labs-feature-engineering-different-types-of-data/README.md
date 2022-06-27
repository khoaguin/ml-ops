# Labs: Feature Engineering with Different Types of Data 
**Lab 1 - Feature Engineering with Weather Data (`C2_W4_Lab_1_WeatherData.ipynb`)**: In this lab, working with weather data, we will 
* Process time-series data with TFX to extract features
* Segment data into windows
* Save data in TFRecord format
* Make it ready for training an LSTM model

**Lab 2 - Feature Engineering with Accelerometer Data (`C2_W4_Lab_2_Signals.ipynb`)**: In this lab, by working with a Human Activity Recognition Dataset (WISDM), we will learn how to 
* Preprocess with TensorFlow Transform
* Use `tf.data.Datasets.window()` to convert time series data to depend on past observations

**Lab 3 - Feature Engineering with Images (`C2_W4_Lab_3_Images.ipynb`)**: In this lab, we will learn how to prepare features with an image dataset, particularly CIFAR-10, using TensorFlow Transform.

## Requirements
`tensorflow==2.6.5`  
`tensorflow_transform==1.4.0`
`apache_beam==2.39.0`