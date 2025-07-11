IRIS RECOGNITION USING DAUGMAN’S ALGORITHM 

🔍 Overview

This project implements an iris recognition system that combines Daugman's Algorithm for iris localization with Artificial Neural Networks (ANN) trained using the Levenberg-Marquardt backpropagation algorithm for classification. The system is developed for high-security applications and tested on the MMU iris dataset, achieving an impressive 99.7% accuracy.

🌐 Features

Iris segmentation using Daugman’s Integro-Differential Operator

Noise reduction and precise circular segmentation

Feature extraction including:

Mean, Standard Deviation, Entropy, RMS, Smoothness, Kurtosis, Energy, Homogeneity, Contrast, Variance

Classification using ANN with Levenberg-Marquardt backpropagation

User-friendly UI with dataset upload, image preprocessing, training, and testing modules

🔖 System Modules

Upload Iris Dataset: Import iris image dataset.

Image Preprocessing: Normalize and resize images for consistency.

Iris Segmentation & Feature Extraction: Apply Daugman’s algorithm and extract iris features.

Train ANN Algorithm: Train the ANN on extracted features.

Iris Classification from Test Image: Upload a test image and classify using trained ANN.

📊 Architecture

The system follows a modular approach:

Iris Segmentation ➔ Feature Extraction ➔ Pattern Matching ➔ Classification (ANN)

🔌 Technologies Used

MATLAB / Python (as per implementation)

ANN Toolbox or Python frameworks

MMU Iris Database

OpenCV (for image preprocessing)

🎯 Results

The system achieves 99.7% accuracy on the MMU iris dataset.

Processes up to 1400 images with correct iris segmentation and classification.

Confusion matrix and output labels indicate high reliability.

⚡ Advantages

High accuracy and low false acceptance rate

Efficient noise reduction and segmentation

Adaptable to real-time and security-intensive applications

❌ Limitations of Previous Systems

High dependency on quality of images

Complex iris patterns not well handled

Limited scalability and real-time performance

✅ Proposed Enhancements

Real-time recognition support

Integration with edge computing

Broader dataset support for inclusivity

Focus on privacy and ethical implementation

📚 References

A comprehensive list of 20+ academic references including:

Alaa S. Al-Waisy (2018)

Arun Ross and Cunjian Chen (2018)

Abhishek Gangwar & Akanksha Joshi (2017)

R. Raghavendra et al. (2017)

MariaDe Marsico (2016)

📁 Dataset

MMU Iris Database: Used for both training and testing phases.

📊 Accuracy Summary

Training Accuracy: ~99.7%

Testing Accuracy (ANN): ~96% with general test images

🚀 How to Run

Clone this repository.

Run the run.bat or main script file (MATLAB/Python).

Use GUI to upload dataset, preprocess, segment, train ANN, and test.

git clone https://github.com/Ashwitha313Iris-Recognition-System
.git
cd Iris-Recognition-System

# Run the GUI or script file

💪 Contribution

Feel free to fork this repo, suggest improvements, or raise issues!

✨ Conclusion

The proposed system demonstrates an advanced, accurate, and efficient iris recognition technique, leveraging mathematical precision from Daugman’s algorithm and learning capabilities of neural networks. It's suitable for biometric security in real-time and sensitive environments.

Keywords: Biometric Identification, Iris Recognition, Daugman Algorithm, Levenberg-Marquardt, ANN, Pattern Recognition

