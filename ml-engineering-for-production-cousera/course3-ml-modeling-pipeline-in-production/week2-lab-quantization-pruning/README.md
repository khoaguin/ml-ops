# Lab: Quantization and Pruning
In this lab, we will get some hands-on practice with the mobile optimization techniques discussed in the lectures. These enable reduced model size and latency which makes it ideal for edge and IOT devices. We start by training a Keras model then compare its model size and accuracy after going through these techniques:
- post-training quantization
- quantization aware training
- weight pruning

## Requirements
`tensorflow==2.8.2`  
`tensorflow_model_optimization==0.7.2`  
