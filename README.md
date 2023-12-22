# CatsVsDogs-Classifier

This is a basic Deep learning project that classifies/identifies images of cats and dogs.

# Dataset
The data set has been taking from this [link](https://www.kaggle.com/competitions/dogs-vs-cats/data).
The dataset contains images of cats and dogs. There are two sets it this link, the training set, and the testing set.
The training set contains labeled images of cats and dogs, while the testing set contains unlabeled images.

# Aim
Our motive is to use the training set to prepare a CNN model that can predict the class of the image given to it as a cat or a dog.

# Setup
1. Clone this repository.
```
git clone https://github.com/Shivansh20128/CatsVsDogs-Classifier.git
```

2. Download the dataset at the provided link. You will find two folders in the dataset, for training and testing. Put the both the training and testing set folders at the same location as the script file.
1. Run the script code snippets one by one. This will help you better understand the flow of the code.
1. It may happen that you face some errors in the import statements. In that case, kindly install the required module. For example, in case tensorflow module is not found, run the command "pip install tensorflow".
1. The training part run 10 epochs, so it takes some time, depending on your system configuration, it may take from 30 mins to 2 hours. 
1. At the end, you can see the model performance from the testing set. 
1. The script also provides the option to test a custom image. Feel free to test any image. Two images are provided separatly for that purpose (dog.jpeg and cat.jpg).

# Source
cat.jpg - https://www.google.com/url?sa=i&url=https%3A%2F%2Fstock.adobe.com%2Fsearch%3Fk%3Dcat&psig=AOvVaw0brGyHODLzkMafF-gmVYIf&ust=1703341435033000&source=images&cd=vfe&ved=0CBIQjRxqFwoTCKDdl7ufo4MDFQAAAAAdAAAAABAE

dog.jpeg - https://www.google.com/url?sa=i&url=https%3A%2F%2Fen.wikipedia.org%2Fwiki%2FList_of_most_popular_dog_breeds&psig=AOvVaw2WoiiisWBVEp3R1kgF3wlf&ust=1703339481867000&source=images&cd=vfe&opi=89978449&ved=0CBIQjRxqFwoTCNiL6qigo4MDFQAAAAAdAAAAABAI
