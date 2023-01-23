
# Road Segmentation Fully Convolutional Neural Network
Road segmentation using fully convolutional networks is a technique used in computer vision to locate and classify objects in an image. This technique uses convolutional neural networks (CNNs) to segment the image into different parts, such as roads, vehicles, and buildings. Fully convolutional networks are more computationally efficient compared to traditional methods and can handle large, high-resolution images. By utilizing this technique, it is possible to accurately detect and classify objects in an image in real-time.

# Index
- [Prerequisites](#Prerequisites)
- [Neural network architecture](#Neural-network-architecture)
- [Some results](#Some-results)
- [Setup](#Setup)
    - [Frameworks and Packages](#Frameworks-and-Packages)
    - [Dataset](#Dataset)
- [Start](#Start)
    - [google colabotory](#colab)

- [Result](#Result)

- [Future Scope](#Future-Scope)

## Prerequisites
```
pip install pandas numpy Pillow tensorflow matplotlib ipython base64
```
## Neural network architecture
The project start loading a vgg model so implements an FCN - Fully Convolutional Network

![new41](https://user-images.githubusercontent.com/83110202/214049630-b4cbeb20-bdae-43a2-97c0-b347ccb9ad89.jpg)

## Some results
<img width="400" alt="Screenshot 2023-01-23 183945" src="https://user-images.githubusercontent.com/83110202/214048051-fd7e2035-e267-40fb-9919-e5507190f326.png">
<img width="400" alt="Screenshot 2023-01-23 184021" src="https://user-images.githubusercontent.com/83110202/214048059-9662da03-039c-4a1b-81b3-2bcf27559800.png">

## Setup
#### Frameworks and Packages
Make sure you have the following is installed:
 - [Python 3](https://www.python.org/)
 - [TensorFlow](https://www.tensorflow.org/)
 - [NumPy](http://www.numpy.org/)
 - [Matplotlib](https://matplotlib.org/)
 - [Pillow](https://pillow.readthedocs.io/en/stable/)
#### Dataset
The project dataset can be download here [Kitti Road dataset](http://www.cvlibs.net/datasets/kitti/eval_road.php)

## Start
 You can get the colab link [here](https://colab.research.google.com/drive/1POUdfvGhR3a_nlNK44-k2UpevEVkcbmO?usp=sharing)

## Result
Road segmentation using an FCN-8 is a project that utilizes deep learning techniques to identify and classify various components in an image or video, such as the road surface, vehicles, pedestrians, and other objects. The goal of this project is to improve the accuracy and efficiency of tasks such as autonomous driving or traffic management by accurately identifying the different components in an image or video. The FCN-8 model has been found to be particularly effective in road segmentation, with a precision of 95.78% and a recall of 96.8% on testing and validation datasets, outperforming traditional CNN models.

## Future Scope
The Road Segmentation project compared the performance of two models, FCN-8 and CNN, on a specific dataset. However, it did not explore the use of other CNN architectures, such as Xception, InceptionV3, and ResNet50, to determine their potential effectiveness in road segmentation. To further improve the accuracy and understanding of the road segmentation task, it would be beneficial to study the performance of these additional CNN models and compare their results to the FCN-8 and CNN models previously used. This could provide insight into how the choice of neural network architecture affects the accuracy of road segmentation.
