### Deep Learning for Medical Diagnostics
This project uses deep learning methods to diagnose medical conditions from chest X-ray images by identifying features and categorizing patients into one of 20 disease classes.

### Contributions
Implementing this model can significantly speed up patient care, improve diagnostic accuracy, and increase radiologist productivity.

### Dataset
The data is sourced from the public [ChestX-ray8](https://arxiv.org/abs/1705.02315). 

This dataset contains 108,948 frontal-view X-ray images of 32,717 unique patients.

After balancing the data, I employed 6,000 examples for training, 2,000 examples for validation, and 2,000 examples for testing.

<br>

<img width="732" alt="Screenshot 2024-07-09 at 2 30 58 PM" src="https://github.com/willy61412/Skincare_Product_Information_Web_Scraper/assets/133930618/60d6fae5-052b-4132-a279-db97831caede">

### Model
The model utilizes a CNN with 5 convolutional layers, Batch Normalization, LeakyReLU activations, and a sigmoid output layer. 

It was optimized using the Adam optimizer, with increased epochs and applied dropout regularization, and early stopping to prevent overfitting.

### Results
- Test accuracy of 67.55% (Expert accuracy ranges from 70-90%).
- High AUC scores (above 0.80) in 16 out of 20 classes, calculated using the testing dataset.

<br>

  ![1720053893680](https://github.com/willy61412/Skincare_Product_Information_Web_Scraper/assets/133930618/e5eaf8f7-b97f-4baf-9186-e452001267eb)

