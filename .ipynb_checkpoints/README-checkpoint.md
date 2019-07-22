#  Sentiment Analysis [![GitHub license](https://img.shields.io/github/license/Naereen/StrapDown.js.svg)](https://github.com/cviejom/Investment-and-Trading/blob/master/LICENSE) [![Awesome Badges](https://img.shields.io/badge/badges-awesome-green.svg)](https://naereen.github.io/badges/)

Sentiment Analysis End to End Deployment Project Using SageMaker
---------------------------------------
This project will demonstrate the SageMaker deployment capabilities! In this project we will construct a recurrent neural network for the purpose of determining the sentiment of a movie review using the IMDB data set. The model will be create using Amazon's SageMaker service. In addition, we will deploy the model and construct and a simple web app that will interact with the deployed model.

The notebook and Python files provided here, result in a simple web application which interacts with a deployed recurrent neural network performing sentiment analysis on movie reviews. 

**General Outline**<br>
General outline for SageMaker using a notebook instance.

1. Download or otherwise retrieve the data.
2. Process / Prepare the data.
3. Upload the processed data to S3.
4. Train a chosen model.
5. Test the trained model (typically using a batch transform job).
6. Deploy the trained model.
7. Use the deployed model.

**Project Notebooks:**
1. SageMaker Project.ipynb

Data
----
The project data is located in the web please use this link: [Project Data](http://ai.stanford.edu/~amaas/data/sentiment/)<br>


Project Details
---------------
The project is separated into 3 parts with associated notebooks for each one of them:<br>
**End to End Implementation:** Please see [Data Exploration](https://github.com/cviejom/Sentiment-Analysis-Web-Application/blob/master/SageMaker%20Project.ipynb)<br>

Project Resources
-----------------
Paper explaining the techniques utilized on Sentiment analysis https://pdfs.semanticscholar.org/c521/80a8fe1acc99b4bf3cf3e11d3c8a38e2c7ff.pdf<br>
Udacity Git Commit Message Style Guide http://udacity.github.io/git-styleguide/<br>
Sentiment analysis Wikipedia Description https://en.wikipedia.org/wiki/Sentiment_analysis

Contributing
------------
Please see [CONTRIBUTING.md](https://github.com/cviejom/Investment-and-Trading/blob/master/CONTRIBUTING.md) if you want to help

Licence
-------
The MIT License (MIT) <br>
Copyright (c) 2019, carlos viejo <br>
May be redistributed under the terms specified in the [LICENSE](https://github.com/cviejom/Plagiarism-Detection/blob/master/LICENSE) file.

About this Project
------------------
This project was created as a part of the assigments from Udacity, **Machine Learning Engineering** nanodegree