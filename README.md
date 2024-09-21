Here's an elaborated version of the paragraph for your GitHub README:

---

# Underwater Image Quality Assessment

This project focuses on evaluating the quality of underwater images using a Mean Opinion Score (MOS). The MOS value, which provides a quantitative measure of image quality, is embedded directly onto each image for easy reference. Two widely used image quality assessment techniques, BRISQUE (Blind/Referenceless Image Spatial Quality Evaluator) and NIQE (Natural Image Quality Evaluator), are employed to calculate the MOS.

The project is divided into several key stages:

### Part 1: Dataset Creation
In the first part of the project (`Underwater Image Quality Assessment Part 1.ipynb`), the dataset is created by preprocessing a collection of underwater images. After preprocessing, the MOS values are calculated and the corresponding image paths are stored in a text file. These values, along with the image paths, are crucial for further model training and evaluation. The processed dataset is saved to the specified drive location for ease of access in subsequent steps.


![image](https://github.com/user-attachments/assets/8c4594cd-bc36-4ab0-a0ef-7ef18a17249a)


### Part 2: Data Storage and Preparation
In the second part (`Underwater Image Quality Assessment Part 2.ipynb`), the MOS values and their respective image paths are read from the text file. This part focuses on organizing the dataset, ensuring that each image is correctly paired with its MOS value for training and testing purposes.

### Part 3: Model Training, Hyperparameter Tuning, and Evaluation
The final part (`Underwater Image Quality Assessment Part 3.ipynb`) involves training machine learning models to predict the MOS based on the underwater image data. Various CNN architectures are explored, followed by hyperparameter tuning to improve the model’s performance. The evaluation of results is done using key metrics such as Spearman Rank Correlation Coefficient (SRCC), Kendall Rank Correlation Coefficient (KRCC), Pearson Linear Correlation Coefficient (PLCC), and Root Mean Square Error (RMSE).


![image](https://github.com/user-attachments/assets/7a2714c2-d8cc-4be0-a85d-ee79bb00467f)

![image](https://github.com/user-attachments/assets/7f39261a-b9bb-460c-b0fa-7f9d6537888a)


Through this comprehensive approach, the project aims to enhance underwater image quality assessment, enabling accurate predictions of image quality and offering insights into model performance.

---
