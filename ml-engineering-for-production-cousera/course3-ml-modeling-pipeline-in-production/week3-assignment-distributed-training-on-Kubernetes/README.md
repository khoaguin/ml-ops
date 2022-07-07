# Assignment: Distributed Multi-worker TensorFlow Training on Kubernetes

In this assignment, we will scale out TensorFlow distributed training using Google Cloud Kubernetes Engine (GKE) and Kubeflow TFJob. We will train an MNIST classification model using TensorFlow multi-worker distributed strategy. We wil use Kubeflow TFJob to configure, submit and monitor distributed training jobs on a Google Kubernetes Cluster (GKE).In particular, we will
1. Deploy `TFJob` components to Google Kubernetes Engine.
2. Configure multi-worker distributed training jobs using `TFJob`.
3. Submit and monitor `TFJob` jobs.

## Environment
We use Qwiklabs and Google Cloud Platform in this assignment with instructions in `DistributedMulti-workerTensorFlowTrainingOnKubernetes-Qwiklabs.html`.