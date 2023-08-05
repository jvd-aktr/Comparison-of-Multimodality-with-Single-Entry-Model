## Problem Statement:
In this work, we will analyze Multimodal Machine Learning models along with single-entity models and compare their performances, challenges, and pitfalls. More concretely, two data entities (textual and image) will be trained and tested in Multimodal architectures like Long Short-Term Memory (LSTM) model and in contrast, will also be fitted to the current state-of-the-art single entity model like Support Vector Machine (SVM) for textual data and Convolutional Neural Networks (CNN) for image data and, finally, we will deeply investigate their outputs.

## Dataset:
We chose the LAION-400M dataset, which comprises 400 million image-text pairs that have been filtered with CLIP. The textual data provides descriptions of the image, making it an ideal dataset for conducting a comparative analysis of single-entity and multimodality models. Given the massive size of the dataset and the limitations of our computational resources, we focused solely on the first subset of the dataset, (part-00000-5b54c5d5-bbcf-484d-a2ce-0d6f73df1a36-c000.parquet)

## Data Downloader:
The LAION-400M Dataset does not provide the image and text data directly. It only provided Excel files of image links and corresponding text in the column.
