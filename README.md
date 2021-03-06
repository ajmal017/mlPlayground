# mlPlayground

My particular Machine Learning Playground, used to explore some techniques for regression and classification, mainly focused on using Deep Learning techniques.

---
### Willing to play with:

**1. Topics:**
- [ ] Image Recognition
  - [x] Digit/Character Recognizer
  - [x] Face Recognizer
  - [ ] Emotion Recognizer
  - [ ] Image Captioning
- [ ] Language Translation
- [ ] Speech Recognition
- [x] Sentiment Analysis
- [x] Natural Language Processing

**2. Deep Learning Models:** 
- [x] Convolutional Neural Networks
- [ ] Recurrent Neural Networks
  - [x] Long Short-term Memory
  - [x] Gated Recurrent Unit
- [ ] Deep Residual Learning 
- [ ] Generative Adversarial Networks
- [ ] Style Transfer
- [x] Autoencoders

**3. Kaggle Playground:** 
- [ ] [Corporación Favorita Grocery Sales Forecasting](https://www.kaggle.com/c/favorita-grocery-sales-forecasting)
- [ ] [House Prices: Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)
- [x] [Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic)
- [x] [Mushroom Classification](https://www.kaggle.com/uciml/mushroom-classification/)
- [ ] [CIFAR-10 - Object Recognition in Images](https://www.kaggle.com/c/cifar-10)
- [ ] [Zoo Animal Classification](https://www.kaggle.com/uciml/zoo-animal-classification)
- [x] [Digit Recognizer](https://www.kaggle.com/c/digit-recognizer#tutorial)
- [x] [Dogs vs Cats](https://www.kaggle.com/c/dogs-vs-cats-redux-kernels-edition)
- [ ] [Leaf Classification](https://www.kaggle.com/c/leaf-classification)
- [ ] [Forest Cover Type Prediction](https://www.kaggle.com/c/forest-cover-type-prediction)
- [ ] [Humpback Whale Identification](https://www.kaggle.com/c/whale-categorization-playground/)
- [ ] [Plant Seedlings Classification](https://www.kaggle.com/c/plant-seedlings-classification/kernels)
- [ ] [Denoising Dirty Documents](https://www.kaggle.com/c/denoising-dirty-documents)
- [ ] [Carvana Image Masking Challenge](https://www.kaggle.com/c/carvana-image-masking-challenge/)
- [ ] [What's Cooking?](https://www.kaggle.com/c/whats-cooking)
- [ ] [Spooky Author Identification](https://www.kaggle.com/c/spooky-author-identification)
- [x] [SMS Spam](https://www.kaggle.com/uciml/sms-spam-collection-dataset)
- [x] [Sentiment Analysis on Movie Reviews](https://www.kaggle.com/c/sentiment-analysis-on-movie-reviews)
- [ ] [Santa's Uncertain Bags](https://www.kaggle.com/c/santas-uncertain-bags)
- [ ] [Freesound General-Purpose Audio Tagging Challenge](https://www.kaggle.com/c/freesound-audio-tagging/)
- [x] [Facial Keypoints Detection](https://www.kaggle.com/c/facial-keypoints-detection)
- [ ] [Partly Sunny with a Chance of Hashtags](https://www.kaggle.com/c/crowdflower-weather-twitter)
- [ ] [New York City Taxi Fare Prediction](https://www.kaggle.com/c/new-york-city-taxi-fare-prediction)
- [ ] [Store Item Demand Forecasting Challenge](https://www.kaggle.com/c/demand-forecasting-kernels-only)
- [ ] [TGS Salt Identification Challenge](https://www.kaggle.com/c/tgs-salt-identification-challenge/data)

---
### Installation
#### General packages
```
conda install -c conda-forge opencv=3.2.0
conda install -c conda-forge tensorflow
conda install -c conda-forge keras
conda install -c conda-forge dlib=19.4
```


#### TensorFlow [GPU](https://nitishmutha.github.io/tensorflow/2017/01/22/TensorFlow-with-gpu-for-windows.html) (Windows)

1. Install VS2015
2. Download and install CUDA Toolkit v8.0 or above (https://developer.nvidia.com/cuda-downloads)
	* Leave your existing driver in place. After starting the installer, deselect the option to install the 
	  driver that comes bundled with the installer. The driver you have now will work with CUDA 8.
3. Download cuDNN version 5.1 library for Windows 10 (https://developer.nvidia.com/cudnn)
4. Extract the cuDNN files into CUDA Toolkit directory (do not replace the folders)
5. Ensure after installing CUDA Toolkit, the CUDA_HOME is set in the environmental variables. 
6. `conda install tensorflow-gpu`
