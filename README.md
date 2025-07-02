# Cat-Dog-prediction

Cat vs Dog Image Classification using SVM
This project implements a complete machine learning pipeline to classify images of cats and dogs using a Support Vector Machine (SVM) classifier. Built in Python and optimized for Google Colab, this notebook walks users through the entire process — from uploading image data, training the model, to predicting new test images with visual output.

Project Highlights
Complete ML Pipeline: Upload ➝ Preprocess ➝ Train ➝ Test ➝ Save

Custom Dataset Upload: Accepts user ZIP files containing train_cat/ and train_dog/ image folders

Image Preprocessing: Resizes images to 64x64, flattens into vectors, and normalizes pixel values

Model Training: Uses SVC with RBF kernel for binary classification

Evaluation: Outputs training & validation accuracy, and classification report

Model Saving/Loading: Save trained model as .pkl and reuse for future predictions

Test Prediction with Confidence: Upload any test image to classify it as cat or dog with visual confidence bar chart

 Technologies Used
Python 3.x

Google Colab (for interactive environment)

Libraries:

numpy, matplotlib, PIL

scikit-learn (SVC, train_test_split, accuracy_score)

pickle (model saving/loading)
