# Labs: Feature Engineering with Different Types of Data 
**Lab 1 - Feature Engineering with Weather Data (`C2_W4_Lab_1_WeatherData.ipynb`)**: In this lab, we will 
* Process time-series data with TFX to extract features
* Segment data into windows
* Save data in TFRecord format
* Make it ready for training an LSTM model

**Lab 2 - Simple Feature Engineering (`C2_W2_Lab_2_Feature_Engineering_Pipeline.ipynb`)**: In this lab, we will dive deeper into TensorFlow Transform to do feature engineering on the [Census Income dataset](https://archive.ics.uci.edu/ml/datasets/Adult). More specifically, we will
* ingest data from a base directory with `ExampleGen`
* compute the statistics of the training data with `StatisticsGen`
* infer a schema with `SchemaGen`
* detect anomalies in the evaluation data with `ExampleValidator`
* preprocess the data into features suitable for model training with `Transform`

**Lab 3 - Feature Selection (`C2_W2_Lab_3_Feature_Selection.ipynb`)**: In this lab, we practice feature selection: the act of picking the set of features that are most relevant to the target variable. This helps in reducing the complexity of your model, as well as minimizing the resources required for training and inference. This has greater effect in production models where you maybe dealing with terabytes of data or serving millions of requests.

## Requirements
`tensorflow==2.6.5`  
`tensorflow_transform==1.4.0`
`apache_beam==2.39.0`