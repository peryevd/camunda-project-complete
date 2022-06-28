### Install:
 - clone project: ```https://github.com/KotskinKotskin/camunda-excamad.git```
 - ```npm install```
 - fill src/config/settings.js with own value
 - ```npm run serve``` (start dev server) 
 - OR
 - ```npm run build``` (produce html,js,css in to /dist/)
 ### Or Docker: 
 - ```docker run -d -p 8080:8080 kotovdenis/excamad:latest```
 ### Settings: 
 - go to excamad url
 - select settings
 - insert camunda url REST endpoint(``` http://localhost:8080/engine-rest/``` by default)