![](https://drive.google.com/uc?id=1BMn975n0e6nexZ7lnyM2CWjbXd9Dhc_2)
...is a simple tool to create neural networks with zero code visually. Its primary aim differs from other UI-based machine learning tools in that it aims to be *powerful* and *flexible* without sacrificing *simplicity* and *intuitiveness*.

## Structure

- Quasar uses a *hierarchy* system to represent the structure of a neural network, offering a high amount of control.

- Layers can be added to or deleted from the hierarchy, and their outputs can either be funneled into the next layer sequentially by default or configured to allow alternative structures such as recurrent networks.

- Optimization algorithms and loss functions are defined in the *compilation* element of the hierarchy, which is always the last step of the network.

- Quasar projects are saved in the Quasar Intermediate Format (.qif), which stores data about the neural network in a single condensed file. Quasar projects can be exported to TensorFlow, PyTorch, and ML.NET models.

## Build Instructions
This repo can be cloned in Visual Studio.

## Documentation
Documentation for Quasar is currently in the works and will be released soon.

## Licensing
Quasar is under the MIT License.
