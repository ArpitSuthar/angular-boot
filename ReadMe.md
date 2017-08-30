# Angular Boot

This project is based on Angular [Tutorial](https://angular.io/tutorial) and it's integration 
with Spring Boot Project

## Plugins Used

Project makes use of below plugin for build
* maven clean plugin : clears target and static folder
* maven frontend plugin : used for installation of NPM, Node
and Angular CLI and execution of related task during build.
* spring boot plugin : used for fat jar creation and live reload
during development

## Angular Features

Project demonstrates few of the basic feature of a Angular App which are list below

* Angular Component
* Angular FormsModule : for two way binding
* Angular RouteModule : for routing with in application
* Angular HttpModule : for communication with backend HTTP service
* Angular Service : How to create service for backend communication and dependency Injection of such services

## Tools

* Intellij Idea
* Microsoft VS Code : with below Plugins
    * Angular Language Service
    * Angular v4 TypeScript Highlight
    * ESLint
    * HTML Snippets
    * Node.js Modules Intellisense
    * npm & npm intellisense
    * TSLint
* Live Reload Plugin for Chorme / Firefox
    
### How to build / run the proect

* build : `mvn clean install`
* run : `mvn clean spring-boot:run`

### Live Reload Step-up

1. Start application using spring boot , this also starts a livereload server within JVM.
2. Excute `npm run build-dev` this will watch for any changes in frontend project and compile them and move to static directory
3. Enable LiveReload extension in Chrome / FireFox 