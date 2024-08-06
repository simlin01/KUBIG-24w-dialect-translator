# **경상도-표준어 Dialect Translator** 🌐
*Transform your sentences from Standard Korean to 경상도 Dialect effortlessly!*

## 🚀 **Project Overview**
Welcome to our 경상도-표준어 Dialect Translator project! This repository is the culmination of our journey to bridge the linguistic gap between Standard Korean and the rich 경상도 dialect, using cutting-edge Transformer models.

### **Why This Project?**
Dialect translation is an under-explored area in Natural Language Processing (NLP). While much focus is given to translating between different languages, regional dialects pose unique challenges and opportunities. Inspired by the scarcity of such tools, especially for Korean dialects, we embarked on this project to provide a seamless translation experience.

## 🧠 **How It Works**
This translator leverages the **Transformer architecture**—the same technology that powers many state-of-the-art NLP models. By training on a curated dataset of 경상도 dialect and standard Korean sentences, our model learns the nuanced linguistic patterns and delivers accurate translations.

### **Tokenizer & Preprocessing**
To prepare our dataset for the Transformer model, we implemented several key preprocessing steps:

- **Data Cleaning**: Removed special characters and non-Korean text using regular expressions to maintain data consistency.
- **Tokenization**: Used a morpheme-based tokenization approach for Standard Korean input and word-level tokenization for 경상도 dialect output. This allowed for better handling of the linguistic variations between the two forms.
- **Handling Irregularities**: Managed outliers and irregular data patterns, such as colloquialisms and speech disfluencies, which are common in dialect data.

These preprocessing steps ensured that the data fed into the model was of high quality, leading to more accurate translations.

### **Key Features**
- **Dialect Awareness**: Translates Standard Korean sentences into authentic 경상도 dialect.
- **Transformer Model**: Based on the "Attention is All You Need" architecture.
- **Performance Optimized**: Fine-tuned with BLEU score evaluation to ensure high-quality output.
<!--
## 📊 **Project Structure**
Here's a brief overview of what you'll find in this repository:

- **`data/`**: Contains the dataset used for training, including pre-processed and tokenized data.
- **`models/`**: Houses the Transformer models and training scripts.
- **`inference/`**: Tools for testing the model on new input sentences.
- **`notebooks/`**: Jupyter notebooks with exploratory data analysis, model training, and evaluation.
-->
## 💻 **Getting Started**
1. **Clone this repository**:
   ```bash
   git clone https://github.com/jchung02/dialect-translator.git
2. **Navigate to the project directory**:
   ```bash
   cd dialect-translator
3. **Install the required dependencies**
   ```bash
   pip install -r requirements.txt
## 📈 **Results**
Our model has been tested rigorously, achieving impressive BLEU scores that reflect its translation accuracy:

- **Model Version 1**: BLEU Score - *0.7643*
- **Model Version 2**: BLEU Score - *0.6826*

For more detailed results and inference examples, check out our `results/` folder!

## 🎓 **Contributors**
This project was brought to life by the dedicated efforts of KUBIG-24W-basic-study-dl-team4:

- **박제재**
- **박세훈**
- **심승현**
- **배지원**
- **정하연**

## 📄 **License**
This project is licensed under the MIT License—see the LICENSE file for details.
