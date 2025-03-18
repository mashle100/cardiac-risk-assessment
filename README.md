# Heart Health Detection Website

## Overview
This project is a web-based application designed to detect the likelihood of being prone to heart attacks using logistic regression. It is intended for educational purposes only and is not a substitute for professional medical advice or diagnosis. The tool provides a basic prediction based on user input and demonstrates the integration of machine learning algorithms into a web application.

## Features
- **Frontend**: An intuitive interface for users to input their health data.
- **Backend**: Processes user inputs and predicts the risk of heart attacks using a logistic regression model.
- **Machine Learning**: Implements logistic regression to analyze health data.

## Purpose
This project served as a stepping stone for my journey into:
- Web development (both frontend and backend).
- Understanding and applying machine learning algorithms.
- Building end-to-end applications that combine web technologies and data science.
- Authentication, cookies, sessions, and databases.
- Backend technologies like Node.js and MongoDB.

## Limitations
- The predictions made by this website are not accurate and should not be used for medical purposes.
- The logistic regression model is simplistic and based on limited data.

## How It Works
1. Users input health-related data through the website.
2. The backend processes the input and uses a logistic regression model to make predictions.
3. The result is displayed on the frontend, indicating the likelihood of being prone to heart attacks.


## Getting Started
#### Setting up Node Server
```
npm install
```

#### Initializing Python Environment
```
python -m venv venv
pip install -r requirements.txt
```

#### Activating Python Environment
```
python/venv/Scripts/activate
```

#### Running the Server (Within Python Environment)
```
nodemon index.js
```

#### Setting up Environment Variables
```
dbUrl = Connection String
secretSessionKey = Session Key
prediction_script_path = Local Path of prediction_script.py
```


## Acknowledgments
This project helped me dive into web development and machine learning, combining the two fields into a practical application. It was a valuable learning experience that introduced me to the challenges and opportunities of building full-stack applications.







