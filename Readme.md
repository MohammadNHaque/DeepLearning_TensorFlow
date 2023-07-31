# Deep Learning with Python: Neural Networks (complete tutorial)
## Build, Plot & Explain Artificial Neural Networks with TensorFlow

By: Mauro Di Pietro; 
Published in: [Towards Data Science](https://towardsdatascience.com/deep-learning-with-python-neural-networks-complete-tutorial-6b53c0b06af0);
Date: Dec 18, 2021

# Setup
For this tutorial, we will use `TensorFlow` and `Keras`.

```bash
$ python --version
Python 3.10.6

# Create and Activate Virtual Environment
$ python -m venv envPyTensorFlow
$ source envPyTensorFlow/bin/activate

# Install Tensorflow
(envPyTensorFlow) $ pip install tensorflow
(envPyTensorFlow) $ pip show tensorflow
Name: tensorflow
Version: 2.13.0
Summary: TensorFlow is an open source machine learning framework for everyone.
Home-page: https://www.tensorflow.org/
Author: Google Inc.
Author-email: packages@tensorflow.org
License: Apache 2.0
```

Install `ipykernel` to run `.ipynb` files:
```bash
(envPyTensorFlow) $ pip install ipykernel
```

Install Otehr required packages:
```bash
(envPyTensorFlow) $ pip install tensorrt
(envPyTensorFlow) $ pip install matplotlib
(envPyTensorFlow) $ pip install shap
```

In addition to those packages, it is recommened (optional) to install `ipywidgets` for configure Jupyter Notebook automatically:
```bash
(envPyTensorFlow) $ pip install ipywidgets
```

We need to install teh following packages if we want to visualise the Model using `TensorFlow` util library:
```bash
(envPyTensorFlow) $ pip install pydot
(envPyTensorFlow) $ sudo apt install graphviz
```
## Now Use the Installed Packages to [Design the Neural network](py_DL_TF_NeuralNetwork.ipynb)