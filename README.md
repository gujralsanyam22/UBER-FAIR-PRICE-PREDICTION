# UBER-FAIR-PRICE-PREDICTION

## Table of Content
  * [Demo](#demo)
  * [Overview](#overview)
  * [Motivation](#motivation)
  * [Technical Aspect](#technical-aspect)
  * [Installation](#installation)
  * [Run](#run)
  * [Deployement on Heroku](#deployement-on-heroku)
  * [Directory Tree](#directory-tree)
  * [To Do](#to-do)
  * [Bug / Feature Request](#bug---feature-request)
  * [Technologies Used](#technologies-used)
  * [Team](#team)
  * [License](#license)
  * [Credits](#credits)
  
  
## Demo
Link: [https://uber-riders-api.herokuapp.com/:](https://uber-riders-api.herokuapp.com/)

image-link:data:image/jpeg;base64,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
## Overview
The main objective of project is to design an algorithm which will tell the fare to be charged for a passenger. Machine learning algorithms are used to develop a regression model.

## Motivation
What could be a perfect way to utilize unfortunate lockdown period? Like most of you, I spend my time in cooking, Netflix, coding and reading some latest research papers on weekends. The idea of classifying indian currency struck to me when I was browsing through some research papers. I couldn't find any relevant research paper (and of course dataset!) associated with it. And that led me to collect the images of Indian currency to train a deep learning model using [this](https://github.com/hardikvasa/google-images-download) amazing tool.

## Technical Aspect
This project is divided into two part:
1. Training a deep learning model using Keras. (_Not covered in this repo. I'll update the link here once I make it public._)
2. Building and hosting a Flask web app on Heroku.
    - A user can choose image from a device or capture it using a pre-built camera.
    - Used __Amazon S3 Bucket__ to store the uploaded image and predictions.
    - Used __CSRF Token__ to protect against CSRF attacks.
    - Used __Sentry__ to catch the exception on the back-end.
    - After uploading the image, the predictions are displayed on a __Bar Chart__.
    
    ## Installation
The Code is written in Python 3.7. If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:
```bash
pip install -r requirements.txt
```
## Run
> STEP 1
#### Linux and macOS User
Open `.bashrc` or `.zshrc` file and add the following credentials:
```bash
export AWS_ACCESS_KEY="your_aws_access_key"
export AWS_SECRET_KEY="your_aws_secret_key"
export ICP_BUCKET='your_aws_bucket_name'
export ICP_BUCKET_REGION='bucket_region'
export ICP_UPLOAD_DIR='bucket_path_to_save_images'
export ICP_PRED_DIR='bucket_path_to_save_predictions'
export ICP_FLASK_SECRET_KEY='anything_random_but_unique'
export SENTRY_INIT='URL_given_by_sentry'
```
Note: __SENTRY_INIT__ is optional, only if you want to catch exceptions in the app, else comment/remove the dependencies and code associated with sentry in `app/main.py`

#### Windows User
Since, I don't have a system with Windows OS, here I collected some helpful resource on adding User Environment Variables in Windows.

__Attention__: Please perform the steps given in these tutorials at your own risk. Please don't mess up with the System Variables. It can potentially damage your PC. __You should know what you're doing__. 
- https://www.tenforums.com/tutorials/121855-edit-user-system-environment-variables-windows.html
- https://www.onmsft.com/how-to/how-to-set-an-environment-variable-in-windows-10

> STEP 2

To run the app in a local machine, shoot this command in the project directory:
```bash
gunicorn wsgi:app
```

## Deployement on Heroku
Set the environment variable on Heroku as mentioned in _STEP 1_ in the __Run__ section. [[Reference](https://devcenter.heroku.com/articles/config-vars)]

![](https://i.imgur.com/TmSNhYG.png)

Our next step would be to follow the instruction given on [Heroku Documentation](https://devcenter.heroku.com/articles/getting-started-with-python) to deploy a web app.

## Directory Tree 
```
├── app 
│   ├── __init__.py
│   ├── main.py
│   ├── model
│   ├── static
│   └── templates
├── config
│   ├── __init__.py
├── processing
│   ├── __init__.py
├── requirements.txt
├── runtime.txt
├── LICENSE
├── Procfile
├── README.md
└── wsgi.py
```
## To Do
1. Convert the app to run without any internet connection, i.e. __PWA__.
2. Add a better vizualization chart to display the predictions.

## Bug / Feature Request
If you find a bug (the website couldn't handle the query and / or gave undesired results), kindly open an issue [here](https://github.com/rowhitswami/Indian-Currency-Prediction/issues/new) by including your search query and the expected result.

If you'd like to request a new function, feel free to do so by opening an issue [here](https://github.com/rowhitswami/Indian-Currency-Prediction/issues/new). Please include sample queries and their corresponding results.

## Technologies Used

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://keras.io/img/logo.png" width=200>](https://keras.io/) [<img target="_blank" src="https://flask.palletsprojects.com/en/1.1.x/_images/flask-logo.png" width=170>](https://flask.palletsprojects.com/en/1.1.x/) [<img target="_blank" src="https://number1.co.za/wp-content/uploads/2017/10/gunicorn_logo-300x85.png" width=280>](https://gunicorn.org) [<img target="_blank" src="https://www.kindpng.com/picc/b/301/3012484.png" width=200>](https://aws.amazon.com/s3/) 

[<img target="_blank" src="https://sentry-brand.storage.googleapis.com/sentry-logo-black.png" width=270>](https://www.sentry.io/) [<img target="_blank" src="https://openjsf.org/wp-content/uploads/sites/84/2019/10/jquery-logo-vertical_large_square.png" width=100>](https://jquery.com/)

## Team
Sanyam Gujral

## License
[![Apache license](https://img.shields.io/badge/license-apache-blue?style=for-the-badge&logo=appveyor)](http://www.apache.org/licenses/LICENSE-2.0e)

Copyright 2020 SANYAM-GUJRAL

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at
http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

## Credits
- [Google Images Download](https://google-images.com)- This project wouldn't have been possible without this tool. It saved my enormous amount of time while collecting the data. A huge shout-out to its creator.

