A simple machine learning project that uses a Support Vector Machine (SVM) classifier to distinguish between images of cats and dogs.
The model is trained on the Kaggle Dogs vs Cats Dataset, using image preprocessing, feature extraction, and SVM classification.


---
 Project Overview

This project implements an SVM-based image classifier for the Dogs vs Cats dataset.
The objective is to classify each image as either a dog or a cat after converting images into numerical feature vectors.

Since SVMs perform poorly on raw pixels, the project uses image resizing, grayscale conversion, and flattening (or optionally HOG features) to extract meaningful visual information for classification.
Technologies Used

Python

NumPy

OpenCV / PIL

Scikit-learn (SVM, train_test_split, accuracy_score)

Matplotlib (for visualization)



---

 Methodology

1. Load images from dataset


2. Resize each image to a fixed size (e.g., 90×90)


3. Convert to grayscale


4. Flatten into a 1D feature vector


5. Split into train/test sets


6. Train Linear SVM or RBF SVM


7. Predict labels on test data


8. Evaluate using accuracy score

---

📊 Sample Output

Images loaded: 2000  
Labels: 2000  
Feature vector shape: (8100,)  
Test Accuracy: 0.65
