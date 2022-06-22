# Assignment: Feature Engineering with TensorFlow Transform

In this assignment, we will have to build a data pipeline using using [Tensorflow Extended (TFX)](https://www.tensorflow.org/tfx) to prepare features from the [Metro Interstate Traffic Volume dataset](https://archive.ics.uci.edu/ml/datasets/Metro+Interstate+Traffic+Volume).

Upon completion, we will have:
* created an `InteractiveContext` to run TFX components interactively
* used TFX `ExampleGen` component to split your dataset into training and evaluation datasets
* generated the statistics and the schema of your dataset using TFX `StatisticsGen` and `SchemaGen` components
* validated the evaluation dataset statistics using TFX `ExampleValidator`
* performed feature engineering using the TFX `Transform` component