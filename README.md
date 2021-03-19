
# deploy carbrad prediction 
deep learning model deployment using transfer learning(resnet50), flask and  heroku

### CAR brand prediction
Transfer Learning VGG 16 and VGG 19 using Keras
car brand classification Train data and test data
Train data consists of - 3 brand cars -audi,lamborghini, mercedes class each folder consists of audi - 20 images; lamborghini - 19 cars; mercedes - 25

Test data consists of -audi - 9 ; lamborghini - 30 ; mercedes - 19

### what is transfer learning
Transfer learning is a research problem in machine learning that focuses on storing knowledge gained while solving one problem and applying it to a different but related problem.

Transfer learning is a machine learning method where a model developed for a task is reused as the starting point for a model on a second task.

### How to Use Transfer Learning?
You can use transfer learning on your own predictive modeling problems.

Two common approaches are as follows:

### 1)Develop Model Approach
### 2)Pre-trained Model Approach
#### Develop Model Approach
Select Source Task. You must select a related predictive modeling problem with an abundance of data where there is some relationship in the input data, output data, and/or concepts learned during the mapping from input to output data. Develop Source Model. Next, you must develop a skillful model for this first task. The model must be better than a naive model to ensure that some feature learning has been performed. Reuse Model. The model fit on the source task can then be used as the starting point for a model on the second task of interest. This may involve using all or parts of the model, depending on the modeling technique used. Tune Model. Optionally, the model may need to be adapted or refined on the input-output pair data available for the task of interest.

#### Pre-trained Model Approach
Select Source Model. A pre-trained source model is chosen from available models. Many research institutions release models on large and challenging datasets that may be included in the pool of candidate models from which to choose from. Reuse Model. The model pre-trained model can then be used as the starting point for a model on the second task of interest. This may involve using all or parts of the model, depending on the modeling technique used. Tune Model. Optionally, the model may need to be adapted or refined on the input-output pair data available for the task of interest. This second type of transfer learning is common in the field of deep learning.
# Steps to fallow
#### step:1 - Fork or download the code
#### step:2 - unzip the datafolder
#### step:3 - open command prompt in the same folder and Run command  
python app.py
#### step:4 - you will get a flask link to predict locally http://127.0.0.1:5000/
we can see the below screen then upload car image and let the model to predict 
![pred-car](https://user-images.githubusercontent.com/66937023/111770833-eb77bc80-88d0-11eb-88c8-83e828eed3b2.png)

# Fallow ** my blog for deploying this DL model at Heroku - https://www.analyticsvidhya.com/blog/2021/02/ml-model-deployment-with-webhosting-frameworks/

Try to go with Heroku paid service - if you get error as shown below - Compiled slug size: 696.9M is too large (max is 500M).
![herokuerr](https://user-images.githubusercontent.com/66937023/111771219-6e007c00-88d1-11eb-8db3-fabe079c7e10.png)




