# Convolutional Neural Network with Median Layers for Denoising Salt-and-Pepper Contaminations

**This is a [Keras](https://keras.io/) version of Median Layer based CNN denoiser implemented by [Luming Liang](https://sites.google.com/site/lumingliangshomepage/) for removing salt-and-pepper noise**

### Prerequisites

Python 3.6
Cuda, Cudnn, ... 

All python package requirements could be found in requirements.txt. Users can simply run 
** pip install -r requirements.txt **
to install all required python packages.

### Publication

@article{liang2021convolutional,

  title={Convolutional neural network with median layers for denoising salt-and-pepper contaminations},
  
  author={Liang, Luming and Deng, Seng and Gueguen, Lionel and Wei, Mingqiang and Wu, Xinming and Qin, Jing},
  
  journal={Neurocomputing},
  
  volume={442},
  
  pages={26--35},
  
  year={2021},
  
  publisher={Elsevier}
  
}

### Architecture

![Our network](https://github.com/llmpass/medianDenoise/blob/master/results/architecture.JPG)

### Dataset

The training and validation datasets can be found in data directory, we use 91image as the training set, all others as validation sets

### Pretrained models

The pretrained models can be found in pretrained directory

### Some inference results 

![Lena](https://github.com/llmpass/medianDenoise/blob/master/results/lenna.JPG)
![Comparisons with noise2noise on BSD300](https://github.com/llmpass/medianDenoise/blob/master/results/bsd300.JPG)
