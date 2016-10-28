# Tensorflow Demo Notebooks

## Prerequisites

Before being able to run this demo you must have completed the following steps:
* Cloned seldon on your machine and followed the [installation process](http://docs.seldon.io/install.html)
* Installed [tensorflow](https://www.tensorflow.org/versions/r0.11/get_started/os_setup.html#download-and-setup)
* Set up a google cloud account and installed the [gcloud cli](https://cloud.google.com/sdk/) and kubectl (gcloud components install kubectl).

## Running the demo

Once this is done you can run the notebooks in the following order:
* **Tear Down and Set Up**: will delete your cluster if it was already existing, create a new one, install WeaveScope and Seldon on it.
* **Model and Pipeline**: Creates a model, trains it and saves it as a seldon pipeline. Also contains instructions to start tensorboard.
* **Seldon Demo**: Loads a pretrained model on the cluster, starts a microservice to serve prediction and starts a webapp for drawing digits.