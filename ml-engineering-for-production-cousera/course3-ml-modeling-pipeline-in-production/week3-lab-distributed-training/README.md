# Lab: Distributed Strategies with TF and Keras

In this lab, we are going to perform a distributed training strategy using TensorFlow and Keras, specifically the `tf.distribute.MultiWorkerMirroredStrategy`.  
With the help of this strategy, a Keras model that was designed to run on single-worker can seamlessly work on multiple workers with minimal code change. In particular we will:
- Perform training with a single worker.
- Understand the requirements for a multi-worker setup (`tf_config` variable) and using context managers for implementing distributed strategies.
- Use magic commands to simulate different machines.
- Perform a multi-worker training strategy.