# Survey

how to start:
i. npm init
ii. npm start

**how to login**:
postman: 
post methode:- http://localhost:3000/login
Set the body to raw, and select JSON as the type.
In the body, paste:{
  "username": "user",
  "password": "pass123"
}

**survey**:
Create a new POST request.
Set the URL to http://localhost:3000/survey.
Go to the "Auth" tab and add the following :
Auth type: Bearer Token
Pass the Token
Go to the "Body" tab, select raw, and choose JSON as the content type.
In the body, paste the survey details:{
 { "title": "survey start", "questions": ["are you satisfied with our website?", "are you playing today?"] }
 and send.

 **Survey Answer**
 Create a new POST request.
Set the URL to http://localhost:3000/survey/id
Go to the "Auth" tab and add the following :
Auth type: Bearer Token
Pass the Token
Go to the "Body" tab, select raw, and choose JSON as the content type.
In the body, paste the survey details:{
 {
  "answers": [true, false, true]
}

 and send.
 
