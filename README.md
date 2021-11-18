# Text to PDF Mini Project

The task made by this project is to convert a text document to a PDF file. I used NodeJs in this project.


## Input Data

Use the file `input.txt` in this repository as the input.


## Expected Result

The output should be a PDF document based on the contents of the input file.



## Realised Work

**The realised work is inside the server folder**

* I implemented the work using an npm package called **jspdf**, I chose this library because it handles client and server side, so we can easily switch the logic to the frontend.  

I worked on an API, that has two endpoints:  
1- one for simply generating a pdf file out of the existing text file `input.txt`

2- the second endpoint allows you to upload a text file and convert it to a pdf  
  
* I dockerized the project
  
* I implemented unit & e-2-e tests using jest & supertest

* I documented the project using Swagger
## Project Structure

the work realised is in the server folder:

* server.js sets the server port and runs the server
* app.js handles routes
* controllers/pdfController.js handles requests and responses
* services/pdfService.js handles the logic of reading a file and generating a pdf
* /test includes unit and end-2-end tests

## How It Works
````shell script
npm i
npm start
npm run test 
````


**GO TO**: http://localhost:8000/api-docs for documentation and further details


