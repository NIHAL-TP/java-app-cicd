configuring a CI-CD pipeline for a java web app using jenkins.
sonarcube is used for dependency check,which is run on a docker environment
maven is used to build the java app.
docker is used to containerize the app.
on git checkout continuos integration process starts.
first sonarcube checks the dependency then maven buildst the project.
on a successful build continous deployment process starts.
containerize the app and deploy to the web/

