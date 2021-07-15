<p align="center">
  <a href="https://www.perceptilabs.com">
  <img src="./pl_logo.png">
  </a>
</p>

# Breast Cancer Images on Histopathology Slides

This dataset<sup>1</sup> contains images of breast cancer on histopathology slides.

The data can be used to build and train an ML model that can detect breast cancer.

# Structure

This repo contains the following structure:

- **data/**: contains the CSV files and directory with images.
  - **test**: contains **benign** and **malignant** subdirectories of images for testing.
  - **train**: contains **benign** and **malignant** subdirectories of images for training.
- **dataset.csv**: CSV file with all data and the training/test labels.
- **dastaset_pl.csv**: CSV file for use in loading the data in PerceptiLabs.


<p align="center">
  <img src="./sample.png">
</p>

The following shows a partial example of the data stored in the dataset_pl.csv that is used as main example.

| **images** | **labels** |
|------------|--------------|
| data/train/benign/SOB_B_F-14-29960AB-400-015.png |	benign |
| data/train/benign/SOB_B_PT-14-21998AB-400-039.png |	benign |
| data/train/benign/SOB_B_A-14-29960CD-400-004.png |	benign | 


# Community

Got questions, feedback, or want to join a community of machine learning practitioners working with exciting tools and projects? Check out our [Community](https://forum.perceptilabs.com/)!

<sup>1</sup> Dataset Credits: https://www.kaggle.com/forderation/breakhis-400x
