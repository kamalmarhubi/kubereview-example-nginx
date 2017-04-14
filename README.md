# kubereview-example-nginx
Open source Repo to study Image build and deployment to Kube cluster
**************************************************************************************

GitHub repo name = movies

Openshift Project name = opendigital28

Docker Repo & image name = opendigital28/movies:Tag

## Build a new Docker Image with Tag "yellow"
On Dev machine 
command = docker build --tag opendigital28/movies:yellow .

command = docker images 
REPOSITORY             TAG                 IMAGE ID            CREATED             SIZE
opendigital28/movies     yellow              c31512f73196        49 seconds ago      54.28 MB

## Login to Docker Hub
command = docker login
username =  manojshetty
password = s**h*

## Push the Docker Image to Docker Repo 
docker push opendigital28/movies:yellow

## Enter passphrase for new root key with ID 9838bf8:  s***h*

## DockerHub
Public Repo name = opendigital28/movies
Tag Name  Compressed Size   Last Updated
yellow     17 MB            in a few seconds

## Openshift 
Install Openshift - command line tool
oc login https://api.preview.openshift.com --token= ****** 



