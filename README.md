# PetStore-Mock-Server
Created as a solution to Swagger coding exercise

Solution to : Exerise 1
Specification and documentation of a systems Application Programming Interface (API) is an essential part of any architecture documentation and serves multiple stakeholders. In this lab, you will work with OpenAPI specification language to study and experiment with the specification of a RESTful API of a simple PetStore service, use Swagger UI to generate an interactive web-based documentation, and Swagger Codegen to generate a fully functional mock server.
Steps –
Step 1: familiarize yourself with the Swagger toolset:  https://swagger.io/
Step 2: use Swagger Editor and learn key features of the specification language:  https://editor.swagger.io/

Step 3: Use the Swagger online IDE and invoke required API functions for the deliverables. Provide screenshots showing a successful and correct execution of functions including 200 response code and the response body. Response body must be successful without any errors. 

Deliverables –
Screenshot showing a successful invocation of /store/inventory API endpoint.

Screenshot showing a successful invocation of /pet/{petId} endpoint, you can obtain a valid PET ID using the /pet/findByStatus endpoint.

Screenshot showing a successful invocation of the endpoint /store/order (POST), show an example json request payload with a successful response.  
Optional –

Study and use Swagger online Editor to test a YAML specification of a greeter API system. The specification supports posting of a greeting json payload and retrieving of all greetings. Modify the specifications as follows:

Add limit query parameter to the /greetings GET endpoint, limit is an integer value and represents the maximum number of greetings that can be returned by the endpoint.
As per specification, the only currently possible response for /greetings POST endpoint is 200/success, add another possible response of 500/server-error along with a new Error schema consisting of the following fields:
code: an integer with two possible values: 1000, 2000
message: a string with two possible values: “server is too busy”, “greeting already exists”
 
Submit your modified YAML specification, separately in a file (either in .yalm or .txt format) and a screenshot, similar to other deliverables, showing the new API documentation in Swagger UI reflecting above modifications.
