# epistemic_deep_learning

Machine learning, including deep learning, is inseparably connected to uncertainty occurring in various facets. This will discuss the difference between aleatoric and epistemic uncertainty, the two categories of uncertainty, especially in the setting of deep learning. We will also give an example of TensorFlow Probability to visualize the two types of uncertainty.

In this section, we will use TensorFlow Probability (TFP), a Python library built on TensorFlow that makes it easy to combine probabilistic models and deep learning on modern hardware to model uncertainty on a simple synthetic dataset. We will see in this example that we can reduce the epistemic uncertainty but not the aleatoric uncertainty.

We train the model on both the whole dataset and the dataset with fewer points (orange dots in the plot above) and obtain the following result. We can notice at once the model trained on different datasets results in a similar result and adding more data will not reduce the aleatoric uncertainty.

