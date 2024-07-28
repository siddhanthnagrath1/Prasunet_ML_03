# Prasunet_ML_03
# <center><i>Prasunet Company Machine Learning Project - 03</i></center>

# <center>Dog vs Cat Classification</center> 
>

## Problem Statement: 
- Classifying Images of Cats and Dogs using Support Vector Machines (SVM)

### Background
- The task of classifying images of cats and dogs is a fundamental problem in computer vision and machine learning. Accurate classification can be used in various applications such as automated tagging, animal behavior studies, and enhancing search engines. The dataset for this problem is the well-known "Dogs vs. Cats" dataset from Kaggle, which contains a large number of labeled images of cats and dogs.

### Objective
- The objective of this project is to develop a Support Vector Machine (SVM) model that can accurately classify images as either cats or dogs. The model will be trained and tested using the Kaggle "Dogs vs. Cats" dataset.

<br>

## About the Dataset 📊

- Download the dataset from here: [Dataset Download](https://www.kaggle.com/c/dogs-vs-cats/data/)

- The dataset consists of 25,000 labeled images of cats and dogs. The images are divided into a training set and a test set. The training set contains 12,500 images of cats and 12,500 images of dogs, and the test set contains a similar distribution.

<br>



<br>

## How to Set Up This Project 🛠️

This guide walks you through setting up the project's environment.

**1. Install Python 🐍**

If you don't have Python installed yet, head over to the official download page: [Python Download Guide](https://wiki.python.org/moin/BeginnersGuide/Download) and follow the instructions for your operating system (Windows, macOS, or Linux).


**<u>Optional: Creating a Virtual Environment</u>**

1. Install virtualenv (if not already installed):

   If you haven't installed virtualenv, you can do so using pip:
    ```bash
    pip install virtualenv
    ```
2. Create a virtual environment:

    In the terminal and run this command:
    ``` bash
    virtualenv venv
    ```

3.  Activate the virtual environment:

    To activate the virtual environment:
    ``` bash
    venv\Scripts\activate
    ```



**2. Download the Repo 📥**


1. Open your Git client or terminal.
2. Navigate to the directory where you want to clone the repository.
3. Run the following command  

```bash 
git clone https://github.com/siddhanthnagrath1/Prasunet_ML_03
```

**3. Install required Dependencies  📦**
1. Open terminal/cmd.
2. navigate to repo directory
3. Run the following command to install dependencies from requirements.txt:

``` bash
pip install -r requirements.txt
```

**4. Host the project Locally 🌐**

- After installing the required dependencies, run the following command to start the project locally:

``` bash
streamlit run server.py
```
