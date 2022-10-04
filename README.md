# Dmoney-api-jmx

## Tool used
- Apache JMeter

## Scenario of the Project
- Login to user
- Get user list
- Create a user
- Search the newly created user by id
- Search the newly created user by phone number
- Search the newly created user by email
- Update the user phone number
- Delete the user

## How to run the project in GUI mood
- Clone the project or download the zip file
- Unzip the project 
- Open the Jmeter then drag and drop the .jmx file into the jmeter 
- Run the project

## How to run the project and generate HTML Report from command line
- Clone the project
- Keep the project into the jmeter -> bin folder
- Go to the jmeter -> bin folder then open CMD from there
- Run the following command to generate HTML Report

      jmeter -n [non gui mode] -t [location of your jmeter test script] -l [location of the result file] -e -o [location of the output folder]
     
    
- Now go to the report folder and open in a browser

***Note: You can also the medium post to generate HTML Report from command line***

https://medium.com/@suchona/how-to-generate-html-dashboard-reports-in-jmeter-from-the-command-line-7e80b6972708


## HTML Report Screenshot

![image](https://user-images.githubusercontent.com/58165269/193933773-9fb66a62-7995-48f4-8001-171ded61058a.png)

    
  
