# Integrate Artifactory with Jenkins

pre-requisites
An Artifactory server Click here to setup
A Jenkins Server Click here to setup
Integration Steps
Login to Jenkins to integrate Artifactory with Jenkins

## Install "Artifactory" plug-in
Manage Jenkins -> Jenkins Plugins -> available -> artifactory
Configure Artifactory server credentials
Manage Jenkins -> Configure System -> Artifactory
Artifactory Servers
Server ID : Artifactory-Server
URL : Artifactory Server URL
Username : admin
Password : password
Create a Freestyle Project
Create a new job
Job Name : artifactory-project
Source code management
Git URL : get URL here
