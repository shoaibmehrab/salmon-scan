# Welcome to the SalmonScan Dataset

The SalmonScan dataset is a collection of images of salmon fish, including healthy fish and fish with two different types of diseases. The dataset consists of three classes of images:

- Fresh salmon
- Salmon with red skin disease
- Salmon with other diseases

This dataset is ideal for use in various computer vision tasks in machine learning and deep learning applications. Whether you are a researcher, developer, or student, the SalmonScan dataset offers a rich and diverse data source to support your projects and experiments.

So, dive in and explore the fascinating world of salmon health and disease!

## Data Overview

The SalmonScan dataset consists of approximately 1,208 images of salmon fish, classified into three classes:

- Fresh salmon (healthy fish with no visible signs of disease), 456 images
- Salmon with red skin disease, 392 images
- Salmon with other diseases, 360 images

Each class contains a representative and diverse collection of images, capturing a range of different perspectives, scales, and lighting conditions. The images have been carefully curated to ensure that they are of high quality and suitable for use in a variety of computer vision tasks.

The dataset is stored in PNG format and is currently without a split into training, validation, and test sets. However, a typical split would be 60% training, 20% validation, and 20% test, giving the following counts:

| Split    | Fresh Salmon | Red Skin Disease | Other Diseases | Total |
|----------|--------------|------------------|---------------|-------|
| Training | 273          | 235              | 216           | 724   |
| Validation| 91           | 79               | 72            | 242   |
| Test     | 92           | 78               | 72            | 242   |

Whether you are interested in developing new computer vision algorithms, testing existing models, or simply learning about salmon health and disease, the SalmonScan dataset provides an excellent resource for your needs.

## Data Preprocessing

The input images were preprocessed to enhance their quality and suitability for further analysis. The following steps were taken:

1. Resizing: All the images were resized to a uniform size of 600 pixels in width and 250 pixels in height to ensure compatibility with the learning algorithm.

2. Image Augmentation: To overcome the small amount of images, various image augmentation techniques were applied to the input images. These included:
  - Horizontal Flip: The images were horizontally flipped to create additional samples.
  - Vertical Flip: The images were vertically flipped to create additional samples.
  - Rotation: The images were rotated to create additional samples.
  - Cropping: A portion of the image was randomly cropped to create additional samples.
  - Gaussian Noise: Gaussian noise was added to the images to create additional samples.
  - Shearing: The images were sheared to create additional samples.
  - Contrast Adjustment (Gamma): The gamma correction was applied to the images to adjust their contrast.
  - Contrast Adjustment (Sigmoid): The sigmoid function was applied to the images to adjust their contrast.

These preprocessing steps were performed to increase the size of the dataset and make it more diverse and representative, which can improve the performance of the learning algorithm.


