# AZURE-deployment with gitaction

Test deployment recommendation_system Research UoW.

##terminal run

login server flaskup.azurecr.io
login_Registry Flaskup

docker build -t flaskup.azurecr.io

docker login flaskup.azurecr.io

docker push flaskup.azurecr.io

