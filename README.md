# Newman Reporter Allure Using Jsonserver And Postman For macOS


## Technology and Tool Used
- Postman
- Node Js
- newman
- Json-Server
- npm
- Visual Studio Code

## Prerequisites

- You must have installed node js to your system
- Postman
- NPM
- Newman
- Json-Server

## Scenario of this project

- The user can create a user
- The user can create a user by id,name
- The user can get all users
- The user can get individual user by user id
- The user can update a user by user id
- The user can delete a user by user id

## API Documents

https://documenter.getpostman.com/view/16548351/2s946feCjX 

## ## How to run this project

- clone this project
- open this project in visual studio code
## npm install

            sudo npm install
- check the npm version

         npm -v
  
## Newman Install

      sudo npm install -g newman
  
- check the newman version

    newman -v
## Install json-Server

      sudo npm install -g json-server
- check the version

      json-server -v
  
- start the json-server

      json-server --watch user.json
  
- Export collection in the same directory
  
  ## Install Newman Reporter-Allure

        sudo npm install -g newman-reporter-allure

  - then hit the command in the terminal

  ## Usage

  To generate Allure results, specify allure in Newman's -r or --reporters option.

         $ newman run <Collection> -e <Environment> -r allure
         $ newman run <Collection> -e <Environment> -r allure --reporter-allure-export <allure-results-out-dir>
  Use the option --report-allure-collection-as-parent-suite to use the collection name as the parent suite title under the Suites view. This helps when you run multiple collections and want to aggregate them in a single report.

## Generating and Serving Allure report

Allure results will be generated under folder "allure-results" in the root location. Use allure-commandline to serve the report locally.

          $ allure serve

Generate the static report web-application folder using allure-commandline

           $ allure generate --clean

 ### Output: 

 ![image](https://github.com/Mamun104/newman-reporter-allure-using-jsonserver-and-postman/assets/78067017/ce549d46-2139-4274-8037-a991324ed2f9)

![image](https://github.com/Mamun104/newman-reporter-allure-using-jsonserver-and-postman/assets/78067017/2a287661-6282-49fe-8027-80d66caea9e4)


          
