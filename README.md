
#### STORIES DEFINITION
__Create an application that implements the next user story__ 
-  As a merchant, I expect DocomoDigital to expose an API to list all my debit and refund transactions 

__Optionally__ 
-  As a merchant I want to get my transactions filtered by a minimum amount and a specific status. 

#### CONTEXT 
- The application is expected to handle thousands of reqs/secs in the next years (not now) 
- Application is expected to be expanded from domain perspective, so it should be able of handling other domain concepts and other bounded contexts. 
- Several developers will work in the app at the same time Technical specifications

#### TECHNICAL DETAILS
- The application should be written in the Java programming language using SpringBoot framework
- Provided GIT repo will contain the datasource to be consumed from the application. Application MUST consume it from https://github.com/adridev/coding-test/raw/master/DDPG-test.json. It should not copy/paste the json to the actual application.
- The application should expose a REST interface.
- The application should be delivered as a docker image.
- Provide the solution at a GIT repo with any needed instructions to execute the app. Fell free to add any explanation about the arquitecture or the approach taken