# Bell Pepper Leaf Disease Classification Using Fine-Tuned Transfer Learning

<img src="static/img/logo sideprika square2.png" height="300px">

This project is the result of my Thesis on a Computer Science Master's Degree at Nusa Mandiri University. The aim is to develop a CNN model with Transfer Learning to predict bell pepper leaf disease by images using image processing.

## Notebook
The code for this project is contained in the <a href="ipynb/bell_pepper_leaf_desease_classification.ipynb">bell_pepper_leaf_desease_classification.ipynb</a> Jupyter notebook file, which can be viewed and interactively run on platforms like Google Colab.

## Paper
The project has been write into paper and has been published in the Journal of Electronics and Telecommunications / _Jurnal Elektronika dan Telekomunikasi_ (JET) with Grade 2 accreditation on August 31, 2023, Indonesia(🇮🇩).

### Abstract
Leaf diseases of plants are common worldwide. Using image processing, farmers could spot diseases in pepper plants more rapidly and get advice from plant disease experts. In this paper, researchers developed a Transfer Learning classification model for bell pepper leaf disease, with the Transfer Learning model trained on images of healthy and diseased bell pepper leaves. Classification of healthy and diseased bell pepper leaves has been carried out, and fine-tuned Transfer Learning has been applied using several pre-trained CNN models. To achieve the best outcome, four pre-trained models, including MobileNet, VGG16, ResNetV250, and DenseNet121, and three Fully Connected (FC) layer architectures were tested. The Fully Connected (FC) layer with four Transfer Learning architectures achieved the best accuracy value of 99.33% on DenseNet121 architecture with one layer and Cohen’s Kappa value of 0.9865.

DOI : http://dx.doi.org/10.55981/jet.546

### Dataset
This research uses images on a public dataset obtained from Tairu Oluwafemi Emmanuel published in Kaggle entitled <a href="https://www.kaggle.com/datasets/emmarex/plantdisease">PlantVillage Dataset</a>. 

The images available on the dataset are tomato leaf, potato leaf and paprika leaf. However, we're only focused on using the datasets, i.e. just bell pepper leaf images.

### Cited By IEEE Paper :
1. <a href="https://ieeexplore.ieee.org/abstract/document/10415016">GSAtt-CMNetV3: Pepper Leaf Disease Classification using Osprey Optimization</a>

## Implementation App
This repository contains web-based applications built using python, flask and some additional libraries listed in the requirements.

### Back-End
- [x] Python 3.8.5

### Requirements
- [x] Werkzeug <code>2.0.1</code>
- [x] Flask <code>2.0.1</code>
- [x] Numpy <code>1.19.5</code>
- [x] Keras <code>2.4.3</code>
- [x] Tensorflow <code>2.14.0</code>
- [x] Gevent <code>21.1.2</code>
- [x] Pillow <code>8.2.0</code>
- [x] H5py <code>2.10.0</code>
- [x] Gunicorn <code>20.1.0</code>

### Screenshot
<table width="100%">
  <tr>
    <td>
      <h4 align="center">Home Page</h4>
      <img src="static/img/Halaman Beranda Aplikasi2.png"/  width="100%">
    <td>
  </tr>
  <tr>
    <td>
      <h4 align="center">Prediction Page</h4>
      <img src="static/img/Halaman Prediksi Aplikasi2.png"/  width="100%">
    <td>
  </tr>
</table>

### Install App

Choose your local folder destination and do this steps :
```
git clone https://github.com/yuris60/bell_pepper_leaf_desease_classification.git

```

```
pip install -r requirements.txt

```


```
python app.py

```

```
Open Browser and type http://localhost:5000

```

## Citation
We would be very grateful if you were will to cite our paper in your research.

### IEEE
```
Y. Akhalifi,  and A. Subekti, "Bell Pepper Leaf Disease Classification Using Fine-Tuned Transfer Learning," Jurnal Elektronika dan Telekomunikasi, vol. 23, no. 1, pp. 55-61, Aug. 2023. doi: 10.55981/jet.546
```

### Thanks To
Thank you very much to `Dr. Agus Subekti, M.Kom` for his guidance to me during the preparation and development of the project and publication papers. Without him, this project couldn't be completed as it should be.


