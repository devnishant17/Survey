# Survey

how to start:
i. npm init
ii. npm start

how to login:
postman: 
post methode:- http://localhost:3000/auth/login
Set the body to raw, and select JSON as the type.
In the body, paste:{
  "username": "user",
  "password": "pass123"
}

survey:
Create a new POST request.
Set the URL to http://localhost:3000/survey.
Go to the "Headers" tab and add the following key-value pair:
Key: Authorization value:...
Go to the "Body" tab, select raw, and choose JSON as the content type.
In the body, paste the survey details:{
  "title": "Sample Survey",
  "questions": [
    "Q1 What is your name?",
    "Q2 what is your age?"
  ]
}
