
### 1. Dataset Description
This assessment utilizes the **Movie Review Dataset** sourced from the HuggingFace Hub. Designed specifically for sentiment analysis, the data is partitioned into three distinct "mini-sets":

* **Training Set:** 25,000 entries (Supervised Learning).
* **Testing Set:** 25,000 entries (Supervised Learning).
* **Unsupervised Set:** 50,000 entries (Unsupervised Learning).

### 2. Data Structure & Features
Each entry in the dataset consists of two primary columns:

| Column Name | Data Type | Description |
| :--- | :--- | :--- |
| **`text`** | String | The actual content of the movie review. |
| **`label`** | Integer | A numerical representation of the sentiment. |

**Label Encoding:**
* **`0`**: Negative Sentiment (Train/Test sets)
* **`1`**: Positive Sentiment (Train/Test sets)
* **`-1`**: No Label (Unsupervised set only)

### 3. Project Goal & Methodology
The primary objective is to develop two **Natural Language Processing (NLP)** algorithms capable of predicting the sentiment of a given review.
The process will involve processing unstructured text to create meaningful numerical word representations.

We will train and compare two distinct classifiers:

 * Support Vector Machine (SVM): A classical machine learning approach.
 * Long Short-Term Memory (LSTM): A deep learning model.

The set can be found at: https://huggingface.co/datasets/stanfordnlp/imdb
