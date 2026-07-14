# ML Dataset Preprocessing

This repository contains my weekly coursework for the **Machine Learning** course at Universitas Dian Nuswantoro (UDINUS). Each folder corresponds to a set of weeks in the semester and covers a different stage of the typical ML workflow — from data preprocessing, to classical classification algorithms, to neural networks and deep learning, to unsupervised clustering.

The goal of this repo is to document my hands-on practice with core machine learning concepts: cleaning and preparing data, building and evaluating models, and understanding how different algorithms behave on different types of data (tabular, text, and image).

## 📁 Repository Structure

| Weeks | Topic | Description |
|---|---|---|
| Week 2 | Data Preprocessing | Initial exploration and cleaning of raw datasets — handling missing values, encoding, scaling, and preparing data for modeling. |
| Week 5-6 | Classification Algorithms | Implementation of several classic classification methods: Text Classification, K-Nearest Neighbors (KNN), Naive Bayes, and Decision Tree, applied to compare their performance and behavior. |
| Week 7 | Artificial Neural Network (ANN) | Building a simple ANN (`ann_tabularDatasets.ipynb`) to classify tabular data, as an introduction to neural network fundamentals before moving into deep learning. |
| Week 8-9-10 | Deep Learning & CNN | A deep learning module (based on NVIDIA's Fundamentals of Deep Learning curriculum) covering: image classification with MNIST and ASL (American Sign Language) datasets, building a Convolutional Neural Network (`03_asl_cnn`), data augmentation to improve generalization, transfer learning (Doggy Door project), a text-generation exercise (Headline Generator), and a final assessment notebook. |
| Week 11-12 | Regression | Simple Linear Regression and Multivariate Linear Regression, used to predict continuous target variables from one or more features. |
| Week 13-14 | Clustering | Unsupervised learning with K-Means and Hierarchical Clustering to group data without labeled targets. |

### Week 8-9-10 file breakdown
| File | Purpose |
|---|---|
| `00_jupyterlab.ipynb` | Environment setup / intro notebook |
| `01_mnist.ipynb` | Handwritten digit classification with MNIST |
| `02_asl.ipynb` | American Sign Language (ASL) image classification |
| `03_asl_cnn.ipynb` | ASL classification using a Convolutional Neural Network |
| `04a_asl_augmentation.ipynb` | Improving the ASL model with data augmentation |
| `04b_asl_predictions.ipynb` | Running predictions with the trained ASL model |
| `05a_doggy_door.ipynb` | Transfer learning example (image recognition for a "smart" doggy door) |
| `05b_presidential_doggy_door.ipynb` | Extended transfer learning exercise |
| `06_headline_generator.ipynb` | Text generation using deep learning (NLP) |
| `07_assessment.ipynb` | Final assessment/evaluation notebook for the module |

## 🛠️ Tools & Libraries
- Python 3.x
- Jupyter Notebook / Google Colab
- pandas, numpy
- scikit-learn
- TensorFlow / Keras (for the deep learning notebooks)
- matplotlib / seaborn

## 🚀 How to Run
1. Clone this repository
```bash
   git clone https://github.com/sabrinaangel/ml-dataset-preprocessing.git
```
2. Install the required dependencies
```bash
   pip install -r requirements.txt
```
3. Open the notebooks week by week in Jupyter Notebook, VS Code, or Google Colab.

## 👤 Author
Sabrina Angel — Informatics Engineering, Universitas Dian Nuswantoro (UDINUS)

## 📌 Notes
This repository is a collection of weekly learning assignments for coursework purposes and is meant for educational documentation, not production use.
