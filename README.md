# ML-Project
We chose the [Fake and Real News Dataset](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset) for this project. It contains labeled news articles categorized as either *fake* or *real*.

We implemented a **Logistic Regression classifier from scratch** in NumPy to classify news articles based on their textual content.

## 🛠️ Setup Instructions (for Google Colab)

To run the notebook in Google Colab:

1. Download the files `Fake.csv` and `True.csv` from the [Kaggle dataset](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset).
2. Upload them to the following path in your Google Drive: /MyDrive/Colab Notebooks/
3. Make sure the notebook has access to your Drive (via `drive.mount('/content/drive')`).  
   The expected file paths are:  
   /content/drive/MyDrive/Colab Notebooks/Fake.csv  
   /content/drive/MyDrive/Colab Notebooks/True.csv  

If the files are not in the correct location, the notebook will not be able to load the dataset.
