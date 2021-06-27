# Dogs vs Cats classifier

This project takes your photos of cats or dogs and predicts the animal in them with 91% validation accuracy  
(The accuracy can be further improved via building model on top of some pre-trained model)
  
  
# Packages used

python v3.8  
tensorflow v2.5  
keras v2.2. 5  
numpy v1.21.0  
pandas v1.2.4  
matplotlib v3.4.2  
seaborn v0.11.1  
tqdm v4.61.1  
scikit-learn v0.24.2 
Out of these you only need tensorflow, keras and numpy for predictions.  

# Dataset
The datatset being used to train the model is taken from kaggle.  
You can download it from [here](https://www.kaggle.com/c/dogs-vs-cats)  
The dataset consists of 25000 total images of dogs and cats. Data augmentation has been used in the model to generate even more data and improve test accuracy


# Instructions

If you want to train the model, run all the cells in DogsVsCats.ipynb  
To use the model on predictions on your own images, run the cells in Predict.ipynb  
(further instructions commented in notebooks)  
