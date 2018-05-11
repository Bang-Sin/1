# Udacity Machine Learning Capstone Project
## Project Topic: State Farm Distracted Driver Detection
See the Kaggle website for a reference.

https://www.kaggle.com/c/state-farm-distracted-driver-detection



## Download and Unzip the Data Sets:
(Data: https://www.kaggle.com/c/state-farm-distracted-driver-detection/data)

- imgs.zip - zipped folder of all (train/test) images

  https://www.kaggle.com/c/state-farm-distracted-driver-detection/download/imgs.zip

- sample_submission.csv - a sample submission file in the correct format

  https://www.kaggle.com/c/state-farm-distracted-driver-detection/download/sample_submission.csv.zip

- driver_imgs_list.csv - a list of training images, their subject (driver) id, and class id

  https://www.kaggle.com/c/state-farm-distracted-driver-detection/download/driver_imgs_list.csv.zip

### Setup: please operate the following steps:
1. Put the train data set 'imgs/train' near to distracted_driver_detection.ipynb
2. Put the test data set 'imgs/test' to **'imgs/test/test'** near to distracted_driver_detection.ipynb
3. Put the 'driver_imgs_list.csv' file near to distracted_driver_detection.ipynb
4. Create 'submission' folder near to distracted_driver_detection.ipynb for store output results of CNN models.
5. Create 'saved_models' folder near to distracted_driver_detection.ipynb for store models with the best validation loss.



## Software and Libraries:
- Anaconda 3 (or Python 3.5 - Jupyter Notebook)
- Tensorflow
- Keras
- Numpy
- Pandas
- Scikit-learn



## Output Results:
1. CNN_1_test_probability.csv
2. CNN_VGG16_test_probability.csv
3. CNN_ResNet50_test_probability.csv
