# Detecting wireless signal noise in mobile radio communications using spatio-temporal AnoGAN

#### This model ensemble a set of CNN-based and LSTM- based AnoGAN in parallel to simultaneously learn the time- series features of the radio modulation signal and the shape expressed in the complex planes.
#### To design the spatio-temporal AnoGAN, we referred to two papers written by T. Schlegl et al. and M.A. Bashar et al.
#### In addition, it was implemented based on the code uploaded to github by yjucho1 and mdabachar.

## Spatio-temporal AnoGAN Architecture
#### The spatio-temporal AnoGAN learns a radio-modulated signal in a complex plane image and time-series dataset in parallel. 
#### In phase 1, CNN-based AnoGAN examines images appearing in complex planes.
#### In phase 2, LSTM-based AnoGAN takes irregular trend information in radio signals.

![Model Architecture](./images/model_architecture.jpg)



## Prerequisites (my environments)
- Python 3.7, Tensorflow 2.9, Keras, Numpy, Pandas, Matplotlib, OpenCV
- A recent NVIDIA GPU

## Reference
#### 1. https://github.com/mdabashar/TAnoGAN
#### 2. https://github.com/yjucho1/anoGAN
