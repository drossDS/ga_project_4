# **Alzheimer's Classification By Severity In MRI Images**
### Table of contents:
- [Problem Statement](#Problem-Statement)
- [Succinct Formulation of the Question](#Succinct-formulation-of-the-question)
- [Data Acquisition](#Data-Acquisition)
- [Software Requirements](#Software-Requirements)
- [Notebooks](#Notebooks)
- [Executive Summary](#Executive-Summary)

### Problem statement:
>We, *Peacock Data Science Co.*, have been contracted by the Alzheimer's Foundation to create a cutting edge diagnotic tool for the identification of Alzheimer's disease in MRI images. This will greatly reduce the bias and manual labor of having doctors individually analyze the images and having to reach a concensus decision. This will be a jumping off point and a second opinion all wrapped up in one application. <br>
<br>
We see two main powerful uses for our model: <br>
1\) In the early diagnosis of at-risk patients to increase their well-being and developing a treatment plan as early as possible. <br>
2\) In the correct classification of Alzheimer's severity for research groups looking for cures/treatments. <br>
<br>
Alzheimer’s disease is a type of dementia that progressively worsens, first affecting individuals’ memory and eventually attacking areas of the brain responsible for controlling basic cognition and bodily function.<br> 
<br>
For context, Alzheimer’s is one of the leading causes of death in adults 65 and older [[1]]. While there is currently no cure for Alzheimer’s, treatment options are available to slow the progression of the disease [[2]].  Thus, early detection and diagnosis of Alzheimer’s is crucial for effective treatment and disease management [[4]]. Further, identifying patients with early stages of Alzheimer’s may help increase the pool of participants for medical trials which seek to find a cure for this disease.<br> 
<br>
A variety of brain imaging techniques (such as MRIs) can be used to track the progress of dementia and medical imaging is one of the key areas where data science classification methods are currently being explored as a means to help medical professionals interpret the data they collect.<br> 
<br>
To that end, we will build a multiclass image classification model employing Convolutional Neural Networks (CNNs) to classify levels of dementia progression of 6400 MRI images which have been previously categorized into 4 classes:  no dementia, very mild dementia, mild dementia, and moderate dementia.<br> 
<br>
A second goal of this study will be to determine if a binary classification model can more accurately detect very mild dementia by training a CNN exclusively on brain images with no signs of dementia and images with very mild dementia.

![Images of brain mass degenaration](https://www.drugwatch.com/wp-content/uploads/progression-alzheimers-disease.png)
>Source: https://www.drugwatch.com/health/alzheimers-disease/

###  Succinct Formulation of the Question:
>Can we build a neural network that can correctly classify Alzheimer's severity in MRI images of brains? Furthermore, when examining for the earliest signs of the disease is it better to train the model on all levels of severity or just cases of very mild dementia and no dementia?

### Data Acquisition:
>Seeing as how this is a proof-of-concept model and for demonstration purposes only we used publicly available brain MRI images from this Kaggle dataset: https://www.kaggle.com/datasets/tourist55/alzheimers-dataset-4-class-of-images. Origin of the data is unknown and no patient information is included. No data dictionary is attached, the diagnosis of each image is produced from the folder in which the images were allocated.

### Software Requirements:
- Pandas
- sci-kit learn
-
- (We recommend running notebooks on Google colab as software is pre-installed, GPUs are free to use, and the code can run unaltered).

### Notebooks
1. 1_EDA.ipynb
2. 2_manually_built_models.ipynb
3. 3_pretrained_models
4. 4_binary_models.ipynb
5. 

### Executive Summary
>Here is the Executive Summary

[1]: https://www.cdc.gov/aging/aginginfo/alzheimers.htm#:~:text=Alzheimer%27s%20disease%20is%20the%20most,thought%2C%20memory%2C%20and%20language.

[2]: https://www.nia.nih.gov/health/how-alzheimers-disease-treated#:~:text=Treatment%20for%20mild%20to%20moderate%20Alzheimer's%20disease,-Treating%20the%20symptoms&text=Galantamine%2C%20rivastigmine%2C%20and%20donepezil%20are,some%20cognitive%20and%20behavioral%20symptoms.

[4]: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7050025/