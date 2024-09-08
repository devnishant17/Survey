# Survey

how to start:
i. npm init
ii. npm start

**how to login**:
**postman: 
post methode:- http://localhost:3000/login**
Set the body to raw, and select JSON as the type.
In the body, paste:{
  "username": "user",
  "password": "pass123"
}

**survey**:
**Create a new POST request.
Set the URL to http://localhost:3000/survey.**
Go to the "Auth" tab and add the following :
Auth type: Bearer Token
Pass the Token
Go to the "Body" tab, select raw, and choose JSON as the content type.
In the body, paste the survey details:{
 { "title": "survey start", "questions": ["are you satisfied with our website?", "are you playing today?"] }
 and send.

 **Survey Answer**
 **Create a new POST request.
Set the URL to http://localhost:3000/survey/id**
Go to the "Auth" tab and add the following :
Auth type: Bearer Token
Pass the Token
Go to the "Body" tab, select raw, and choose JSON as the content type.
In the body, paste the survey details:{
 {
  "answers": [true, false, true]
} and send
**Thumbnail and exelsheet**


_1._ **Create a new POST request.
Set the URL http://localhost:3000/bonus/thumbnail**
Go to the "Auth" tab and add the following :
Auth type: Bearer Token
Pass the Token
Go to the "Body" tab, select raw, and choose JSON as the content type.
In the body, paste the survey details:{
{
  "imageUrl": "https://example.com/sample-image.jpg"
}
and send.


_2._ 
**Method: GET
URL: http://localhost:3000/bonus/generate-excel**
Go to the "Auth" tab and add the following :
Auth type: Bearer Token
Pass the Token
and click send.
 Note: _The response will be an Excel file with the name survey-results.xlsx.
Postman will allow you to download the file._
 
