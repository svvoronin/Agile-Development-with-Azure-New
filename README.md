# Overview

<TODO: complete this with an overview of your project>

## Project Plan
<TODO: Project Plan

* A link to a Trello board for the project
* A link to a spreadsheet that includes the original and final project plan>

## Instructions

<TODO:  
* Architectural Diagram (Shows how key parts of the system work)>

<TODO:  Instructions for running the Python project.  How could a user with no context run this project without asking you for any help.  Include screenshots with explicit steps to create that work. Be sure to at least include the following screenshots:

* Project running on Azure App Service

* Project cloned into Azure Cloud Shell

* Passing tests that are displayed after running the `make all` command from the `Makefile`

* Output of a test run

* Successful deploy of the project in Azure Pipelines.  [Note the official documentation should be referred to and double checked as you setup CI/CD](https://docs.microsoft.com/en-us/azure/devops/pipelines/ecosystems/python-webapp?view=azure-devops).

* Running Azure App Service from Azure Pipelines automatic deployment

* Successful prediction from deployed flask app in Azure Cloud Shell.  [Use this file as a template for the deployed prediction](https://github.com/udacity/nd082-Azure-Cloud-DevOps-Starter-Code/blob/master/C2-AgileDevelopmentwithAzure/project/starter_files/flask-sklearn/make_predict_azure_app.sh).
The output should look similar to this:

```bash
udacity@Azure:~$ ./make_predict_azure_app.sh
Port: 443
{"prediction":[20.35373177134412]}
```

* Output of streamed log files from deployed application

> 

## Enhancements

<TODO: A short description of how to improve the project in the future>

## Demo 

<TODO: Add link Screencast on YouTube>


![image](https://user-images.githubusercontent.com/6615388/194730741-112e798f-3c2b-4b54-954f-efbbc6cdc6f3.png)



![image](https://user-images.githubusercontent.com/6615388/194758804-401df7ca-0a5a-4758-bcd1-1d9f3900acde.png)

![image](https://user-images.githubusercontent.com/6615388/194759531-5a46fcf9-d84f-4c75-8514-9fbf5694d43e.png)

![image](https://user-images.githubusercontent.com/6615388/194761847-e7a71fc1-1fcb-4fa5-9ba2-d57ac53b06f9.png)

    ```



make install

az webapp up -n flaskml-sergey --resource-group Agile-dev-azure

https://flaskml-sergey-voronin.scm.azurewebsites.net/api/logs/docker

az webapp log tail

python -m flask run

    ```

[![Python application test with Github Actions](https://github.com/svvoronin/Agile-Development-with-Azure/actions/workflows/pythonapp.yml/badge.svg?branch=main&event=deployment_status)](https://github.com/svvoronin/Agile-Development-with-Azure/actions/workflows/pythonapp.yml)
