# Multiclass-image-classification: Rice-leaf-Disease-Dataset
Rice leaf diseases need to be identified and diagnosed in their early stages for timely implementation of effective disease management strategies. Traditional methods of disease detection often rely on visual inspection by experienced agronomists, which can be time-consuming, labour-intensive, and prone to human error. Image classification using machine learning (ML) algorithms presents a promising solution to this problem.

## Background Information
A multi-class image dataset – Rice Leaf Diseases Dataset was obtained from  [Mendeley Data](https://data.mendeley.com/datasets/dwtn3c6w6p/1). It focuses on three major leaf diseases affecting rice plant: **Bacterial Blight (BB), Brown Spot (BS), and Leaf Smut (LS)**. The dataset was downloaded and unzipped, it contains three folders: Bacterial Blight (BB), Brown Spot (BS), and Leaf Smut (LS) which contains the images of the rice leaf affected with these diseases respectively.
After Unzipping, **4684 images** of the above-mentioned classes were found. Due to computational  efficiency, training this large set of images on a local machine can indeed take a significant amount of time so a subset of the images was extracted, **200 images** of each class was extracted using python code to randomly extract the images.

## Project Objectives
1. To pre-process the rice leaf disease dataset, ensuring data compatibility with machine learning algorithms. 
2. To implement and train Six distinct machine learning models: support vector machine, k-nearest neighbour, fully connected neural network, convolutional neural network, Logistic Regression, and Random Forest. 
3. To evaluate the performance of each model using various metrics such as confusion matrix,  classification accuracy, specificity, and sensitivity associated with each disease class. 
4. To conduct hyperparameter tuning for each classifier to optimize their performance and  ensure robustness. 
5. To compare the performance of the trained models and identify the most suitable approach for rice leaf disease classification based on evaluation results. 
