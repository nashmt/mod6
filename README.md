Matt Nash
CSCI 459
Assignment 6

# Directories
This file explains the contents of each directory.
## ADRs
This directory contains records for the architectural design of the project.
## mongo
This directory contains all of the necessary files to build the MongoDB container.
## server
This directory contains all of the necessary files to build the web server container.
## webclient
This directory contains all of the necessary files to build the business logic container.
## mod6_ files
provisionAppPlaybook.yaml --> provisions and runs the application
provisionAppPlaybook.retry --> tries to provision the application again in case it fails
stopAppPlaybook.yaml --> stops the containers
removeAppPlaybook.yaml --> stops all containers and removes all images
