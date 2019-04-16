# Trajectories-Prediction-NN
Study and analysis of Trajectories Prediction with Neural Network Feed-Forward.
The file 'report.pdf' describes the work.

## Installation

The scripts are written in Python 3.6.

This project requires the following Python packages installed:
* numpy
* matplotlib
* pytorch
* tensorboardx: for visualizing the results ( https://github.com/lanpa/tensorboardX )


## Example execution

This command start the training with GPU device and non linear multi-layer model:
```
$ python train.py -c -m
```

This command open TensorBoard session to visualize the results:
```
$ tensorboard --logdir=runs-test
```

The details of training, qualitative results and trained model are saved in folder 'test'.


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


**Note**:
This project has been developed for the course "Image and Video Analysis" ( Università degli studi di Firenze ).


## Authors
* **Francesco Marchetti**

