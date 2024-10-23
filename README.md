# Melanoma Detection Using Custom CNN
> Outline a brief description of your project.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

The project focuses on building a convolutional neural network (CNN) to accurately detect melanoma, a deadly form of skin cancer, from images. Melanoma accounts for 75% of skin cancer-related deaths, and early detection can significantly improve treatment outcomes. The solution aims to assist dermatologists by automating the diagnosis process, thus reducing manual effort and providing faster results.

The dataset used contains 2357 images of various skin conditions, including both malignant and benign types. The data is derived from the International Skin Imaging Collaboration (ISIC) and includes the following diseases:

- Actinic keratosis
- Basal cell carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented benign keratosis
- Seborrheic keratosis
- Squamous cell carcinoma
- Vascular lesion

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Successfully built a CNN-based model to classify skin conditions into nine categories.
- Initial model runs showed signs of overfitting; however, implementing dropout, batch normalization, and data augmentation helped reduce overfitting.
- Class imbalance was handled using data augmentation, which improved the model's performance on underrepresented classes.
- The final model demonstrates potential for assisting dermatologists in early detection of melanoma.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python 3.8
- TensorFlow 2.x
- Keras
- NumPy
- Matplotlib
- Augmentor
- Google Colab (for faster GPU training)
<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was inspired by the need for early and accurate melanoma detection.
- Dataset sourced from the International Skin Imaging Collaboration (ISIC).

## Contact
Created by [@SriPriyaValluru]


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->