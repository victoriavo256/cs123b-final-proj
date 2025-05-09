# cs123b-final-proj
A pair of Google Colab Notebooks that use binary classification models to predict cancer patient outcomes using a dataset from the National Cancer Institute Genomic Data Commons database (https://gdc.cancer.gov/content/next-generation-cancer-knowledge-base).
- Data_Processing.ipynb does preprocesses the data into a machine-readable format
- Models.ipynb trains and runs the machine learning models (Random Forest, SVM, Linear Regression, MLP, SLP)
- clinical.json is the dataset of 279 cancer patient cases

Authors: Sereyvidya Vireak, Victoria Vo, Jerison Wong

Professor: James Casaletto @ San Jose State University

April 2025

# How to run the code
1. Create a folder in your Google Drive. This is where you will be storing the notebook's output.
2. Download the clinical.json dataset and upload it to the folder you just created.
3. In that same folder, create a subfolder called csv.
4. Open Data_Processing.ipynb in Google Colab and update the following line in the first code block to match the path to the folder where you uploaded the clinical.json dataset: PATH = "/content/drive/Shareddrives/123B Project/279_cases/"
7. Run the Data_Processing.ipynb code.
8. Open Models.ipynb in Google Colab and similarly to step 4, update the path variable in the first code block.
9. Run the Models.ipynb code. This notebook may take about half an hour to complete running.
