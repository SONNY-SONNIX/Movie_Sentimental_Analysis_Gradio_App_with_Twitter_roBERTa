  ## Deploying an Interactive Sentiment Analyzer with Gradio and Transformers on Hugging Face
 Python Transformers Gradio PyTorch   
 ### Introduction
 
The Movie Sentiment Analysis App is a practical demonstration of applying Natural Language Processing (NLP) techniques to analyze the sentiment of movie reviews. 

In this project, we leverage Gradio, a user-friendly interface, and Hugging Face's Transformers library, which offers pre-trained NLP models.

The goal is to create an interactive tool that allows users to input movie reviews and receive instant predictions about whether the sentiment expressed in the review is positive, negative, or neutral.

Sentiment analysis plays a pivotal role in understanding public opinion, customer feedback, and user sentiments in various domains, including the film industry.

By providing a user-friendly interface for sentiment analysis, this project showcases the potential for NLP applications and offers a practical solution for analyzing movie sentiments.


# Summary
| Code      | Name        | Published Article |  Deployed App |
|-----------|-------------|:-------------:|------:|
| Capstone Project|The Sentiment Analysis Project| [Article]()| [Deployed App]() |

Gradio_App

Building Machine Learning Applications on huggingface With Gradio ✨


## 📖 Table of Contents

+ Description

+ Dataset Overview

+ Project Setup

+ Building the Sentiment Analysis App

+ Running the App

+ Project Structure

+ License

##  Description 🚀📊

Welcome to Deploying an Interactive Sentiment Analyzer with Gradio and Transformers on Hugging Face! 

This project demonstrates how to build a movie sentiment analysis app using Gradio and Hugging Face's Transformers library. 

Sentiment analysis, also known as opinion mining, is a natural language processing (NLP) task that involves determining the sentiment expressed in a piece of text. 

The app allows users to input movie reviews, and it predicts whether the sentiment of the review is positive, negative, or neutral.

It uses a previously pre-trained hugging text classification model(Twitter-roBERTa-case).

The project showcases a simple sentiment analysis app for movie reviews.

### Dataset Overview 

The dataset used for this project contains movie reviews along with binary sentiment polarity labels. 

It serves as a benchmark for sentiment classification, with labels indicating whether the sentiment is positive or negative. 

Neutral sentiment is also considered as a class.

## Installation and Setup ⚙️🔧 

To get started, follow these installation steps:

# set up the environment on Windows by running the following code.

Make sure you have Python installed on your system.

- Clone this repository to your local machine.
  
  git clone <repository-url>

- Navigate to the project directory.

  cd <project-directory>

- Set up a virtual environment (optional but recommended).

python -m venv myenv

- Activate the virtual environment.

### On Windows:

- myenv\Scripts\activate

  
### On macOS and Linux:

- source myenv/bin/activate

### Install the required packages.

- pip install -r requirements.txt

  ### The Two commands are of the same structure 

1. Activate the python environment 

2. Upgrade pip to its current version 

3. Install the requirements located in requirements.txt: You should be at the root of your env

## 🚀 Usage

### To see how the app works, follow these instructions: 

1. After setting up environment, activating the environment, and installing requirements, type

gradio run <python_script> # in the terminal

This will open the App in your browser

## 👥 Authors
This project is developed and maintained by:

Sonny Agorvor -Otchie feel free to reach out to me with any questions or feedback!

## ✨ Acknowledgments

I would like to express my gratitude to The Azubi Africa team for their valuable contributions to this project.

## 📞 Contact
For any questions, concerns, or suggestions regarding this project, please contact us at otchie.sonny@gmail.com.

Install the required packages to be able to run the evaluation locally.

You need to have Python3 on your system. Then you can clone this repo and being at the repo's root (root :: repo_name> ...) follow the steps below:

Windows:

  python -m venv venv; venv\Scripts\activate; python -m pip install -q --upgrade pip; python -m pip install -qr requirements.txt  
Linux & MacOs:

  python3 -m venv venv; source venv/bin/activate; python -m pip install -q --upgrade pip; python -m pip install -qr requirements.txt  
  
Both long command lines have the same structure, they pipe multiple commands using the symbol, but you may manually execute them one after another.

Create Python's virtual environment that isolates the required libraries of the project to avoid conflicts;

Activate Python's virtual environment so that the Python kernel & libraries will be those of the isolated environment;

Upgrade Pip, the installed libraries/packages manager to have the up-to-date version that will work correctly;

Install the required libraries/packages listed in the requirements.txt file so that it will be allowed to import them into the 

python's scripts and notebooks without any issues.

NB: For MacOs users, please install Xcode if you have an issue.

##Resources

### Quick intro to NLP

[Getting Started With Hugging Face in 15 Minutes>](https://www.youtube.com/watch?v=CMrHM8a3hqw)

[Fine-tuning a Neural Network explained](https://www.youtube.com/watch?v=QEaBAZQCtwE)

Fine-Tuning-DistilBert - Hugging Face Transformer for Poem Sentiment Prediction | NLP(https://www.youtube.com/watch?v=5T-iXNNiwIs)https://www.youtube.com/watch?v=5T-iXNNiwIs

[Introduction to NLP: Playlist](https://www.youtube.com/watch?v=zcW2HouIIQg)

[](https://www.youtube.com/watch?v=zcW2HouIIQg)

[](https://www.youtube.com/playlist?list=PLM8wYQRetTxCCURc1zaoxo9pTsoov3ipY)