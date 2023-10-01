# Welcome to the SalmonScan Dataset

The SalmonScan dataset is a collection of images of salmon fish, including healthy fish and fish with two types of diseases. The dataset consists of two classes of images:

- Fresh salmon 🐟
- Infected Salmon 🦠

This dataset is ideal for various computer vision tasks in machine learning and deep learning applications. Whether you are a researcher, developer, or student, the SalmonScan dataset offers a rich and diverse data source to support your projects and experiments.

So, dive in and explore the fascinating world of salmon health and disease!

## Data Overview

The SalmonScan dataset consists of approximately 1,208 images of salmon fish, classified into two classes:

- Fresh salmon (healthy fish with no visible signs of disease), 456 images
- Infected Salmon containing disease, 752 images

Each class contains a representative and diverse collection of images, capturing a range of different perspectives, scales, and lighting conditions. The images have been carefully curated to ensure that they are of high quality and suitable for use in a variety of computer vision tasks.

The dataset is stored in PNG format and is currently without a split into training, validation, and test sets. However, a typical split would be 60% training, 20% validation, and 20% test, giving the following counts:

| Split      | Fresh Fish 🐟 | Infected Fish 🦠 | Total   |
|------------|---------------|------------------|---------|
| Training   | 273           | 451              | 724     |
| Validation | 92            | 151              | 243     |
| Test       | 91            | 150              | 241     |
| **Total**  | **456**       | **752**          | **1208**|

Whether you are interested in developing new computer vision algorithms, testing existing models, or simply learning about salmon health and disease, the SalmonScan dataset provides an excellent resource for your needs.

## Data Preprocessing

The input images were preprocessed to enhance their quality and suitability for further analysis. The following steps were taken:

1. Resizing 📏: All the images were resized to a uniform size of 600 pixels in width and 250 pixels in height to ensure compatibility with the learning algorithm.

2. Image Augmentation 📸: To overcome the small amount of images, various image augmentation techniques were applied to the input images. These included:
  - Horizontal Flip ↩️: The images were horizontally flipped to create additional samples.
  - Vertical Flip ⬆️: The images were vertically flipped to create additional samples.
  - Rotation 🔄: The images were rotated to create additional samples.
  - Cropping 🪓: A portion of the image was randomly cropped to create additional samples.
  - Gaussian Noise 🌌: Gaussian noise was added to the images to create additional samples.
  - Shearing 🌆: The images were sheared to create additional samples.
  - Contrast Adjustment (Gamma) ⚖️: The gamma correction was applied to the images to adjust their contrast.
  - Contrast Adjustment (Sigmoid) ⚖️: The sigmoid function was applied to the images to adjust their contrast.

These preprocessing steps were performed to increase the size of the dataset and make it more diverse and representative, which can improve the performance of the learning algorithm.

## Usage

To use the salmon scan dataset in your ML and DL projects, follow these steps:

1. **Clone or download** the salmon scan dataset repository from GitHub.
2. **Unzip** the file to access the two folders (FreshFish and InfectedFish).
3. **Load** the images into your preferred programming environment, such as Python.
4. Use standard libraries such as `numpy` or `pandas` to convert the images into arrays, which can be input into a machine learning or deep learning model.
5. **Split** the dataset into training, validation, and test sets as per your requirement.
6. **Preprocess** the data as needed, such as resizing and normalizing the images.
7. **Train** your ML/DL model using the preprocessed training data.
8. **Evaluate** the model on the test set and make predictions on new, unseen data.

## Dataset Download

You can download the dataset using the following link:

<a href="https://www.dropbox.com/scl/fi/nv7kglxmxsy5poo155i61/SalmonScan.zip?rlkey=qggp4bh4kcth8pcf3u6z8qw6r&dl=0" download>
  <img src="https://cdn.icon-icons.com/icons2/37/PNG/64/download_36434.png" alt="Download Icon" width="32" height="32">
</a>

**Note:** The download button is located in the top left corner after clicking the link.

## License

The salmon scan dataset is released under the MIT License, which is an open source license that permits use, modification, and distribution of the software. The full license text can be found in the [LICENSE](LICENSE.txt) file.

## Citation

If you use this dataset in your research or projects, please cite the following reference:

```
@article{SHOAIBAHMED2021,
title = {Fish Disease Detection Using Image Based Machine Learning Technique in Aquaculture},
journal = {Journal of King Saud University - Computer and Information Sciences},
year = {2021},
issn = {1319-1578},
doi = {https://doi.org/10.1016/j.jksuci.2021.05.003},
url = {https://www.sciencedirect.com/science/article/pii/S1319157821001063},
author = {Md {Shoaib Ahmed} and Tanjim {Taharat Aurpa} and Md. {Abul Kalam Azad}},
keywords = {Fish Diseases, Aquaculture, Image Processing, Machine Learning, Support Vector Machine, Salmon Fish}
}
```
