# CNN Kernel Size and Pooling Analysis

## Student Information

* **Student Name:** Reecha Talla
* **Student ID:** 24160377
* **Module:** Machine Learning

---

## Overview

This project explores how kernel size and pooling affect feature learning in Convolutional Neural Networks (CNNs). The study compares different CNN architectures using varying kernel sizes (3×3, 5×5, 7×7) and evaluates the impact of including or excluding pooling layers.

The models are trained and tested on the MNIST dataset, and their performance is analysed using accuracy, loss curves, feature maps, and confusion matrix.

---

## Objectives

* Understand the impact of kernel size on feature extraction
* Analyse the role of pooling in improving generalisation
* Compare multiple CNN configurations
* Visualise feature maps to interpret model behaviour
* Evaluate model performance using confusion matrix

---

## Dataset

The MNIST dataset is used for this project.

* 70,000 grayscale images of handwritten digits
* Image size: 28×28 pixels
* 10 classes (digits 0–9)

Dataset source: http://yann.lecun.com/exdb/mnist/

---

## Models Implemented

Six CNN configurations were tested:

* 3×3 kernel with pooling
* 3×3 kernel without pooling
* 5×5 kernel with pooling
* 5×5 kernel without pooling
* 7×7 kernel with pooling
* 7×7 kernel without pooling

All models use:

* Adam optimizer
* Sparse categorical cross-entropy loss
* Same architecture (except kernel size and pooling)

---

## Results Summary

* Smaller kernels (3×3) provide better feature extraction and performance
* Pooling improves generalisation and reduces overfitting
* Larger kernels (5×5, 7×7) capture broader features but lose fine details
* Models without pooling show signs of overfitting
* Confusion matrix confirms strong classification accuracy

---

## Visualisations

The project includes the following visual outputs:

* Training vs Validation Accuracy
* Validation Accuracy Comparison
* Training vs Validation Loss
* Feature Map Visualisation
* Pooling Effect (Before vs After)
* Confusion Matrix

---

## How to Run

1. Clone the repository:

   ```
   git clone https://github.com/reecha-24160377/cnn-kernel-pooling-analysis.git
   ```

2. Navigate to the project folder:

   ```
   cd cnn-kernel-pooling-analysis
   ```

3. Install required dependencies:

   ```
   pip install -r requirements.txt
   ```

4. Open the notebook:

   ```
   jupyter notebook cnn_kernel_pooling_analysis_24160377.ipynb
   ```

5. Run all cells to reproduce results.

---

## Project Structure

```id="n1vxy2"
cnn-kernel-pooling-analysis/
│
├── cnn_kernel_pooling_analysis_24160377.ipynb
├── cnn_kernel_pooling_report_24160377.pdf
├── README.md
├── LICENSE
├── requirements.txt
```

---

## Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib
* Scikit-learn

---

## Ethical Considerations

Machine learning models may inherit biases from training data. Although MNIST is a simple dataset, real-world datasets may introduce fairness concerns. Additionally, complex models increase computational cost and environmental impact.

---

## Accessibility

* Clear visualisations with labels and titles
* Simple and understandable explanations
* Structured layout for readability

---

## License

This project is licensed under the MIT License.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the software, subject to the inclusion of the original copyright notice.

The software is provided "as is", without warranty of any kind.

---

## References

* Goodfellow, I., Bengio, Y., & Courville, A. (2016). *Deep Learning*. MIT Press
* LeCun, Y., Bengio, Y., & Hinton, G. (2015). *Deep learning*. Nature
* TensorFlow Documentation: https://www.tensorflow.org/
* MNIST Dataset: http://yann.lecun.com/exdb/mnist/

---

## Author

Reecha Talla
Student ID: 24160377
