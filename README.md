# Graybill_Smith_FinalProject

Contained in this repository are the configurations, steps, code, and other files to replicate what was set up for our final project. This repo can be cloned into a docker swarm enviroment and be built deployed via the stpes given in the text files. Faas-flow chaining functions and their handlers were taken from: https://github.com/faasflow/faas-flow-example

The following files are included:

Configuration_Commands.txt - This file contains all the commands used to create VM instances, initialize the docker swarm, install open faas, faas-flow infrastucture, and faas-flow-tower (dashboard).

Docker_Image_Links.txt - This file contains the links to the Docker Hub repositories that house the images that we created and are called in our stack.yml file

flow.yml - This file is the enviromental file that is referenced for all of the functions being build and deployed by stack.yml

stack.yml - This file contains all the configurations for the faas flow chaining functions and our functions that are included in this repository

func1, func2, fake-storage - These directories contain two files each, the Dockerfile used to make their respective docker images and the python handler file that contains the code for each of functions.

Note:
This project was completed for CS 2510 - Distributed Systems at the University of Pittsburgh. The project will build and deploy in the envoiroment explained by the text files, but the functions themselves will throw errors. There was an issue with configurations and there was simply not enought time to figure them out before the deadline
