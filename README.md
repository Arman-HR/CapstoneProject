# Classification of Brain Tumour Subtypes Using Multilayer Perceptrons on Gene Expression Data
This project explores the application of Multilayer Perceptrons (MLPs) for the
classification of brain tumour subtypes based on gene expression profiles.
Using the CuMiDa dataset, we tackle both binary and multinomial classification
problems.

## Contents
- `CapstoneProjectBinaryClassification.ipynb`: Notebook for binary classification of brain tumours.
- `CapstoneProject.ipynb`: Notebook for multiclass classification.
- Preprocessing pipeline using scikit-learn (`SelectKBest`).
- MLP training with TensorFlow/Keras.
- PCA-based visualization of the dataset.
- Evaluation metrics: Accuracy, Confusion Matrix, and classification report.

## Dataset
We use the CuMiDa dataset, which includes gene expression data labeled by brain
tumour subtype. The dataset has 54675 features and includes thousands of
samples grouped by diagnosis. This dataset is downloaded via the internet in
the notebook.

## Requirements
These requirements are installable in the notebook.
- Python 3.8+
- Jupyter Notebook / JupyterLab
- NumPy
- Pandas
- Scikit-learn
- TensorFlow
- Matplotlib
- Seaborn

## Participants
Name                         Student Number
*   Arman Torabi (Team lead) (1058001)
*   Gerrit van Aalst         (1035187)
*   Jesse de Zeeuw           (1058515)
*   Martijn Warnas           (1048740)
*   Thom Veldhuis            (1055805)

## How to use
You can open a notebook and run the cells each for each for getting results.
These results will create graphs and will train the models.

This can be done in any editor of choosing, but we used Google Colab to run it, which can be found here:
[Multiclass Classification](https://colab.research.google.com/drive/1MnhUBwtCo6ipMUybk13JmnIgViu0X0ff?usp=sharing) and [Binary Classification](https://colab.research.google.com/drive/14AetqxlQZz_lUFJzr297AwLOCeCS5_PU?usp=sharing)
