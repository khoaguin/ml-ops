# Assignment: TFX on Google Cloud Vertex Pipelines

TFX is the best solution for taking TensorFlow models from prototyping to production with support for on-prem environments and in the cloud such as Google Cloud's Vertex AI Pipelines.

Vertex AI Pipelines helps us automate, monitor, and govern ML systems by orchestrating the ML workflow in a serverless manner and storing the workflow's artifacts using Vertex ML Metadata.

In this lab, we will automate the development and deployment of a TensorFlow 2.7 classification model which predicts the species of penguins. To do this, we will:

1. Create a TFX Pipeline using TFX APIs.
2. Define a pipeline runner that uses Vertex Pipelines together with the Kubeflow V2 DAG runner
3. Deploy and monitor a TFX pipeline on Vertex Pipelines.