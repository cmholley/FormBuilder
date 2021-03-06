FormBuilder
===========

FormBuilder is a dynamic form building web application that works with dynamic forms and provides sharing functionality. It communicates to a Java Backend located in FormBuilderBackend repo.

### Development Prerequisites
- bower `npm install -g bower`
- gulp `npm install -g gulp`
- npm packages `npm install`

### Getting Started
1. Run `gulp setup`. This runs common setup tasks, especially `bower install` using bower.json.
2. Run `ionic serve`. This uses `ionic.xml` and will serve as local node server. Live updates when you make changes to the code.

### Gulpfile
This repository is configured to deploy to Housuggest `gulp deploy-prod` and HnetDev `gulp deploy-dev` remote sites. Additional documentation [here](https://github.com/DataAnalyticsinStudentHands/DASH-Documentation/blob/master/Code%20Development/Frontend/App-Deployment-to-web-server.md).

### NOTE
This application is not intended to be deployed as a mobile application. Please use [Form Viewer App](https://github.com/DataAnalyticsinStudentHands/FormViewerApp) instead.
