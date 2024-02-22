<div align="center">

# Cervical Cancer EfficientNetV2

[![python](https://img.shields.io/badge/-Python-blue?logo=python&logoColor=white)](https://github.com/pre-commit/pre-commit)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white)](https://www.tensorflow.org)
<a href="https://pytorch.org/get-started/locally/"><img alt="PyTorch" src="https://img.shields.io/badge/PyTorch-ee4c2c?logo=pytorch&logoColor=white"></a>

</div>

## Paper

This is the official implementation of [Penggunaan Variasi Model pada Arsitektur EfficientNetV2 untuk Prediksi Sel Kanker Serviks](https://j-ptiik.ub.ac.id/index.php/j-ptiik/article/view/12656) at J-PTIIK-2023.

## Description

Cervical cancer is one of the diseases that cause the most deaths in women worldwide. This mortality rate is due to lack of awareness of the infection and the absence of obvious early symptoms, so patients only realize their condition is at an advanced stage which is more difficult to treat. With this in mind, early diagnosis is crucial but the lack of trained medical personnel poses a serious problem in diagnosis, especially in areas with limited health resources. Therefore, a method is needed to be able to diagnose cervical cancer. Based on previous research, Deep Learning methods, especially Convolutional Neural Network (CNN), have been used to detect cervical cancer but have poor accuracy. This study uses the CNN model EfficientNetV2 because it is proven to detect images with good performance and effectiveness. datasets.

<br>

## Dataset

The dataset used for training and testing the model consists of X-Ray chest images of Cervical Cancer. The dataset was obtained from [Cervical Cancer Dataset](https://www.kaggle.com/datasets/obulisainaren/multi-cancer)

<br>

## Architecture

![Architecture Model](/Arsitektur_Model.png)


<br>

## Requirements

- [Python](https://www.python.org/?downloads)
- [Jupyter Notebook](https://www.dataquest.io/blog/jupyter-notebook-tutorial/)

## Download and Installation:

1. Clone this repository to your local machine by either clicking on clone button or you can do it form git bash or linux terminal using following command.

```
git clone https://github.com/dunasi4139/Cervical-Cancer-EfficientNetV2.git
```

2. Once you have codes on your local machine now run jupyter on your machine then upload the code and respective dataset to jupyter home.
3. Now you have codes in your jupyter repository or folder now you can see your project on home in jupyter now click on and a new windows with browser will be opened up now click run button and you will see the results.

## How to contribute

1. Fork this repository
2. clone that repository

```
git clone link_of_that_repository
```

3. Make changes that you want in local repository
4. Add those changes

```
git add .
```

5. commmit those changes

```
git commit -m 'name of commit'
```

6. push changes to remote repository
7. create pull request

<br>

## Acknowledgement

- This project is built using the [EfficienNetV2](https://github.com/google/automl) template.
- Thanks to providing the dataset. [Cervical Cancer Dataset](https://www.kaggle.com/datasets/obulisainaren/multi-cancer)

<br>

## Citation

```
@article{Sidik_Utaminingrum_Muflikhah_2023, title={Penggunaan Variasi Model pada Arsitektur EfficientNetV2 untuk Prediksi Sel Kanker Serviks}, volume={7}, url={https://j-ptiik.ub.ac.id/index.php/j-ptiik/article/view/12656}, number={5}, journal={Jurnal Pengembangan Teknologi Informasi dan Ilmu Komputer}, author={Sidik, Duwi Purnama and Utaminingrum, Fitri and Muflikhah, Lailil}, year={2023}, month={Agu}, pages={2116–2121} }
```
