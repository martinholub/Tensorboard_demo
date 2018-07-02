# Tensorboard Demo

 In this repo, there are 2 versions of the classifier, a simple one and a complex one. `input_data.py` retrieves and formats the [MNIST character dataset](http://yann.lecun.com/exdb/mnist/).

# Requirements
* [Tensorflow](https://www.tensorflow.org/install/install_linux#InstallingAnaconda)

# Installation

1. Follow the instructions on the [Anaconda download](https://conda.io/miniconda.html) site to download and install **Miniconda**.

2. Create and activate your environment
```bash
conda create -n dl-test
source activate dl-test
```
3. Install [Tensorflow](https://anaconda.org/conda-forge/tensorflow)
```bash
conda install -c conda-forge tensorflow
```

# Usage

Once you have Tensorflow installed, just run:
```
python simple.py
```
or
```
python complex.py
```

to train your model. You can view the results in Tensorboard after training by typing the following into terminal:
```
tensorboard --logdir=./logs/nn_logs
```

or, for the `complex.py` example:
```
tensorboard --logdir=./logs/mnist_logs
```
Terminal will output an address to visit in your browser. Go to that address to see your tensorboard. That's it!

# Credits

[@Sirajology](https://youtu.be/3bownM3L5zM) who created the original version of the demo together with an introductory video.
