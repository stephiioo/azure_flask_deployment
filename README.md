# azure_flask_deployment
This is the HHA 504 azure flask deployment homework

## Instructions:

Set up a flask application and deploy it on azure app service

## Part 1: Setting up the application

1. Create a github repo that includes a README.md file and name it azure_flask_deployment then copy the url of the repo
2. Open cloud shell and git.clone the copied url
3. Create a directory for the flask app and use the code found in week 2 flaskapp_0 as a starting base
4. Integrate Jinja templating to set up a homepage (base.html) for the app
5. Use app.py to represent the web application and handle incoming requests and route them to the appropriate functions


## Part 2: Deploying it on azure app service
1. Prepare your flask app and make sure you have a requirements.txt file that lists all the python packages required for the app
2. In cloud shell, inout curl -sL https://aka.ms/InstallAzureCLIDeb | sudo bash to install the Azure CLI
3. use az and az login --use-device-code to authenticate with Azure  using a device code flow.
4. Click the provided link and sign in with the generated password
5. In cloud shell enter az webapp up --name stephanie-504-flask --runtime PYTHON:3.9 --sku B1
6. deploy it then push all neccessary changes to gihub with git add ., git commit -m 'faker updates' and git push


Azure deployed link: stephanie-504-flask.azurewebsites.net
