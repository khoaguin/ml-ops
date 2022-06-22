# Labs: Feature Engineering with TFX Transform
**Lab 1 - Simple Feature Engineering (`C2_W2_Lab_1_Simple_Feature_Engineering.ipynb`)**: In this lab, we will get some hands-on practice with the [Tensorflow Transform](https://www.tensorflow.org/tfx/transform/get_started) library (or `tf.Transform`) to do feature engineering on a very simple dataset with only 3 samples. This help understand what's going on under the hood of TensorFlow Transform and Apache Beam.

**Lab 2 - Simple Feature Engineering (`C2_W2_Lab_2_Feature_Engineering_Pipeline.ipynb`)**: In this lab, we will dive deeper into TensorFlow Transform to do feature engineering on the [Census Income dataset](https://archive.ics.uci.edu/ml/datasets/Adult). More specifically, we will
* ingest data from a base directory with `ExampleGen`
* compute the statistics of the training data with `StatisticsGen`
* infer a schema with `SchemaGen`
* detect anomalies in the evaluation data with `ExampleValidator`
* preprocess the data into features suitable for model training with `Transform`

**Lab 3 - Feature Selection (`C2_W2_Lab_3_Feature_Selection.ipynb`)**: In this lab, we practice feature selection: the act of picking the set of features that are most relevant to the target variable. This helps in reducing the complexity of your model, as well as minimizing the resources required for training and inference. This has greater effect in production models where you maybe dealing with terabytes of data or serving millions of requests.

## Requirements
`tensorflow==2.6.0`  
`tensorflow_transform==1.3.0`