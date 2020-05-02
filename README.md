# model-deployment---heroku

The main objective of this repository is to deploy end-to-end model in local and cloud. 

This is my fist application deployment end-to-end in cloud. So for learning purpose I have kept it simple.

I have used here "pycaret" library for training my model and saving it. 

The flow of the project can be seen as :

Model Training using pycaret library -> Deploy & Test the application in local server -> Deploy model in cloud(heroku)

Below is the explanation of each directory:

dataset : This directory contains the "insurance" data set.

src : This directory contains all the necessary files.
      app.py         -> The starting point of the application
      home.html      -> Web page to collect data and predict in real time.
      deployment.pkl -> Saved model after training.

TrainModelUsingPycaret.ipynb  -> Python code to train the model using pycaret.

Google colab is used to run the "TrainModelUsingPycaret.ipynb" file.


