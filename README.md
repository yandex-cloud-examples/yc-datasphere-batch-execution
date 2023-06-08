This repository contains an example of how to use Yandex DataSphere. You can find the full tutorial at https://cloud.yandex.ru/docs/datasphere/tutorials/batch-code-execution.

Based on a use case of a simple convolutional neural network (CNN), the tutorial shows how to set up deployment of a model trained in Yandex DataSphere using Yandex Cloud Functions. The example is based on this PyTorch tutorial: https://pytorch.org/tutorials/beginner/blitz/cifar10_tutorial.html.

`my_nn_model.py`: Neural network architecture.

`train_classifier.ipynb`: Download a training sample of the CIFAR10 dataset and train the neural network described in the `my_nn_model.py` file. The trained model's weights will be saved to the `cifar_net.pth` file in the project storage.

`test_classifier.ipynb`: Upload the model architecture and weights created during model training. The model is used for predictions based on the test sample.
