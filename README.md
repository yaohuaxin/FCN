# Environment Setup
```bash
$ conda install theano  
The following NEW packages will be INSTALLED:

    libgpuarray: 0.7.6-h14c3975_0    
    pygpu:       0.7.6-py27h035aef0_0
    theano:      1.0.3-py27hfd86e86_0

$ git clone https://github.com/Lasagne/Lasagne.git
wiht commit: a61b76fd991f84c50acdb7bea02118899b5fefe1

$ cd Lasagne
$ pip install -e .

$ export THEANO_FLAGS='device=cuda0,floatX=float32'
$ python environmentCheck/useGPUForTheano.py
```

# FCN
Fully Convolutional Networks

# Fully Convolutional Networks (FCN) for 2D segmentation
Refer: http://deeplearning.net/tutorial/fcn_2D_segm.html
Code here: http://deeplearning.net/tutorial/code/fcn_2D_segm/
Under Fold: FCN-For2DSegmentation-with_Lasagne/
