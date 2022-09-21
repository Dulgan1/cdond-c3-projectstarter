#Give Your Application Auto-deploy Superpowers

[![Dulgan1](https://circleci.com/gh/Dulgan1/cdond-c3-projectstarter.svg?style=svg)](https://circleci.com/gh/Dulgan1/cdond-c3-projectstarter)

This project covers the utilization of  CI/CD pipeline to give the Udapeople web app auto deploy superpowers.

The config.yml file under .circler folder/directory contains yhe sequential jobs to build the backend node.js app with frontend/add new features, test both backend and frontend, scan for vulnerabilities, configure the server on AWS, deploy backend and frontend, run migrations, and delete old stack of resources to save costs.

Ansible is used for configuration managements in the server, it contains plays for configuring the server for the app by installing dependencies and starting the the application.It also contains the plays for install and configuring node-exporter for prometheus server monitoring.

The rest of the files are the web app files needed to be build.
