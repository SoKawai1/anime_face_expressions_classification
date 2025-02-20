# Anime Face Expressions Classification
![Frame 14 (2)](https://github.com/user-attachments/assets/5e1a8709-e2e9-47e5-962a-7894cfa560c7)
This projec
t focuses on classifying anime facial expressions using deep learning techniques. The repository contains various Jupyter notebooks that guide you through the process of data collection, preprocessing, model training, and evaluation.

## Table of Contents

- [Project Overview](#project-overview)
- [Notebooks](#notebooks)
- [Installation](#installation)
- [Usage](#usage)

## Project Overview

The goal of this project is to build a model that can accurately classify different facial expressions in anime characters. By leveraging convolutional neural networks (CNNs) and a curated dataset of anime faces, the project demonstrates the end-to-end workflow from data acquisition to model deployment.

## Notebooks

1. **Data Collection and Parsing**
   - `danbooru_images_parsing.ipynb`: Scrapes images from the Danbooru dataset based on specific tags to gather a diverse set of anime faces.

2. **Data Preprocessing**
   - `anime_faces_cropping.ipynb`: Processes the collected images to detect and crop faces, ensuring uniformity in the dataset.
   - `anime_facial_expressions_df.ipynb`: Creates a DataFrame containing image paths and corresponding labels for facial expressions.

3. **Model Development**
   - `anime_face_expressions_classification_v1.ipynb`: Initial exploration and training of a CNN model by using [data set]([https://pages.github.com/](https://www.kaggle.com/datasets/mertkkl/manga-facial-expressions)) taken from Kaggle . 
   - `anime_face_expressions_classification_v2.ipynb`: Refinement of the model with improved architecture, new data set and hyperparameters for better performance.

## Installation

To run the notebooks and experiments locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/SoKawai1/anime_face_expressions_classification.git
   cd anime_face_expressions_classification


Set up a virtual environment:

bash
python3 -m venv env
source env/bin/activate  # On Windows, use `env\Scripts\activate`
Install the required dependencies:

bash
pip install -r requirements.txt
Note: Ensure you have a requirements.txt file listing all necessary packages. If it doesn't exist, you can create one by exporting your current environment's packages.

Usage
After setting up the environment and installing the dependencies:

Data Collection:

Run the danbooru_images_parsing.ipynb notebook to scrape and download images.
Data Preprocessing:

Execute the anime_faces_cropping.ipynb notebook to detect and crop faces from the downloaded images.
Use the anime_facial_expressions_df.ipynb notebook to label the images and prepare the dataset.
Model Training and Evaluation:

Open and run anime_face_expressions_classification_v1.ipynb for initial model training.
Proceed to anime_face_expressions_classification_v2.ipynb for model improvements and evaluation metrics.
Ensure that each notebook is run in the specified order to maintain the workflow consistency.
