# Trajectories-Prediction-NN
Study of Trajectories Prediction with Neural Network Feed-Forward

report.pdf describes

## Installation

The scripts are written in Python 3.6.

This project requires the following Python packages installed:
* numpy
* matplotlib
* pytorch
* tensorboardx: for visualizing the results ( https://github.com/lanpa/tensorboardX )


## Example execution

This command start the training with gpu device and model non linear multi-layer:
```
$ python train.py -c -m
```

this command open TensorBoard session to visualize the results:
```
$ tensorboard --logdir=runs-test
```


## Command line arguments
```
    -h, --help                     show this help message and exit
    -c, --cuda		           use gpu/cpu for training ( default: cpu )
    -m, --model_nonLinear	   use model linear single-layer or non linear multi-layer ( default: single-layer )
    --batch_size		   batch size to use during training (default: 32)
    --max_epochs		   number for epochs for training (default: 600)
    --past_len                     past length (default: 20)
    --future_len                   future length(default: 40)
    --learning_rate                learning rate of training(default: 1e-5)

```

### Usage
```
train.py [-h] [-t | -p] [-p0 P0] [-q Q] [-r0 R0] [-n N] [-k K] [-v VEHICLE] [path]
```

**Note**:


## Authors
* **Francesco Marchetti**

