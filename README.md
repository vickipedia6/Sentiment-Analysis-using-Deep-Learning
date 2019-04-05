# Sentiment-Analysis-using-Deep-Learning

This project was developed as a part of Udacity's Deep Learning Nanodegree. In this project, i have created a Recurrent neural network from scratch using pytorch and deployed it using Amazon Sage Maker.

## Getting Started

Just run all the cells in the ipynb notebook. Tune the hyper parameters for better accuracy.
Get the data from [here](http://ai.stanford.edu/~amaas/data/sentiment/)

### Prerequisites

* Python 3
* Numpy
* MatPlotLib
* OpenCv
* Pytorch 

### Install

#### Setting up a Notebook Instance

The deployment project which you will be working on is intended to be done using Amazon's SageMaker platform. In particular, it is assumed that you have a working notebook instance in which you can clone the deployment repository.

1 . First, start by logging in to the AWS console, opening the SageMaker dashboard and clicking on Create notebook instance.

2. You may choose any name you would like for your notebook. Also, using ml.t2.medium should be all that is necessary for the project.      In addition, an ml.t2.medium instance is covered under the free tier.

3. Next, under IAM role select Create a new role. You should get a pop-up window that looks like the one below. The only change that        needs to be made is to select None under S3 buckets you specify.

4. Once you have finished setting up the role for your notebook, your notebook instance settings should look something like the image      below.

5. Note that your notebook name may be different than the one displayed and the IAM role that appears will be different.

6. Next, scroll down to the section labelled Git repositories. Here you will clone the https://github.com/vickipedia6/Sentiment-Analysis-using-Deep-Learning.git.


You're done! Click on Create notebook instance.

Your notebook instance is now set up and ready to be used!

You can access your notebook using the Action "Open Jupyter".
 
### Project results

This project has met the following specifications:
* The submission includes all required files, including notebook, python scripts and html files.
* Answer describes what the pre-processing method does to a review.
* The build_dict method is implemented and constructs a valid word dictionary.
* Notebook displays the five most frequently appearing words.
* Answer describes how the processing methods are applied to the training and test data sets and what, if any, issues there may be.
* The train method is implemented and can be used to train the PyTorch model.
* The RNN is trained using SageMaker's supported PyTorch functionality.
* The trained PyTorch model is successfully deployed.
* Answer describes the differences between the RNN model and the XGBoost model and how they perform on the IMDB data.
* The test review has been processed correctly and stored in the test_data variable.
* The predict_fn() method in serve/predict.py has been implemented.
* The model is deployed and the Lambda / API Gateway integration is complete so that the web app works (make sure to include your         modified index.html).
* Answer gives a sample review and the resulting predicted sentiment.

## Losses

### Model :

BCELoss: 0.305068384019696


## Built With

* Python 3

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

## Acknowledgments

* The data comes from Udacity.

