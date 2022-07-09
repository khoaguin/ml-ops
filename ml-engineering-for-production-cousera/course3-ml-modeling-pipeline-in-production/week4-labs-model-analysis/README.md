# Labs: Model Analysis & Debugging
**Lab 1 - Tensorflow Model Analysis (`C3_W4_Lab_1_TFMA.ipynb`)**: In this lab, we will practice using Tensorflow Model Analysis (TFMA) to compute and visualize metrics across different slices of your data. This is an important step in production systems since we don't want to deploy a model that will only work well for a particular case or just a subset of potential users. More so, this kind of analysis can be crucial in applications where fairness is a top priority. TFMA allows you to set up the feature slices we want to monitor and quickly spot where the model is having issues. In particular, we will:
* Study and setup the starter files to use with TFMA
* Make a configuration file to tell TFMA what data slices it will analyze and the metrics it will compute
* Visualize TFMA's outputs in a notebook environment
* Generate a time series of a model's performance
* Compare the performance of two models so we can decide which one to push to production

*Note: if the `tfma.view.render_...` functions does not show the visualizations, you need to allow cookies for the third parties in the browser*

**Lab 2 - Model Analysis with TFX Evaluator (`.ipynb`)**: In the previous lab, we've used TFMA as a standalone library. In this lab, we will see how it is used by TFX with its Evaluator component. This component comes after your Trainer run and it checks if the trained model meets the minimum required metrics and also compares it with previously generated models. In particular, we will go through a TFX pipeline that prepares and trains the the binary classifier on the Census Income dataset (same model as in lab 1).


## Requirements
### Lab 1
`tensorflow==2.6.0`  
`tensorflow_data_validation==1.1.0`  
`tensorflow-transform==1.0.0`  
`tensorflow-model-analysis==0.32.0`  
`apache-beam==2.32.0`

### Lab 2
`tfx==1.7.0`  
`apache-beam==2.39.0`