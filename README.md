# Facial Emotion Recognition (FER) ML Project
## About the Project

> Facial Emotion Recognition is a Machine Learing model based on Convolutional Neural Network (CNN) architecture which is a Deep Learning Algorithm and trained on the FER2013 dataset and FER+ label dataset.

> It is the ML model that uses a CNN ML algorithms to identify, analyze and recognize emotional states of a person by analyzing their facial expressions.

> The model works by analyzing facial features such as eyebrows, eyes, nose, mouth, and cheeks to detect patterns of muscle movement that correspond to different emotions.

## Built With

- Tensorflow
- Keras
- OpenCV


## Getting Started

### Prerequisites

> The project requires the following dependencies pacakges to be installed in your environment/machine.

* python >= 3.7.9
* keras >= 2.4.3
* tensorflow >= 2.3.1
* opencv >= 4.4
* sklearn >= 0.23
* numpy >= 1.18.5
* pandas >= 1.1.2
* matplotlib >= 3.3.1

## Installation

### Running the project in your environment/machine.

- Open terminal or git bash on the project folder

1. Clone the repo.

```sh
git clone https://github.com/Amit-TheOne/Facial-Emotion-Recognition
```

2. Change to Facial-Emotion-Recognition directory.

```sh
cd Facial-Emotion-Recognition
```

3. Install required packages.

- Use [anaconda](https://www.anaconda.com/) to easily install Keras and Tensorflow in addition to necessary cuda drivers to run the model on GPU.
- Packages can be easily installed using either pip or conda.

> My recommedation will be to use conda

```sh
conda install package_name
pip install package_name
```

- Replace package_name with the package name you want to install 
- Install all dependencies packages as stated above, read individual technology documentation for further guide to install

# Usage

1. To train the model use the following command.

```sh
 python fer.py
```

2. The model can make predictions on saved images by providing the image path using the following command.

```sh
 python img_predict.py img_name.png
```

2. It can also predict on saved videos.

```sh
  python vid_predict.py vid_name.mp4
```

3. It can also predict in a live camera.

```sh
  python live_cam_predict.py
```


### Model created By 
* Amit Dewangan 👨‍💻 
* Akash Kumar Verma 
* Deepanshu Pawar 
* Ayush Kumar Sahu

[Connect with Amit Dewangan 🚀][Amit-Dewangan]

### Built with ❤️ by the Maintainers 


[//]: #
[Amit-Dewangan]: https://linktr.ee/amit.dewangan