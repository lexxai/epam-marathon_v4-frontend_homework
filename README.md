# Frontend related codebase

|Tool| Version |
|----|---------|
|Angular| 18.2 |


To run application, follow below steps:
1) npm install -g @angular/cli - install angular cli globally;
2) Install node js by following roles ^18.19.1 || ^20.11.1 || ^22.0.0 -  18.x but higher than 18.19.1, 20.x but higher than 20.11.1, 22.x but lower than 23.0.0
3) npm install - install all dependencies;
4) npm run run - run application;
5) in /src/app/services/api.service.ts change DOT_NET_API_URL and PYTHON_API_URL to your local backend url;

The folder with comparison of JS/React/Angular can be found at this path:
./src/app/comparison/

To run React project:
1) go to the following directory:
   ./src/app/comparison/react.js/
2) open terminal in this directory
3) run command 'npm install'
4) run command 'npm start'
5) open the link returned by the terminal in the browser
6) to add correct link to your backend:
  - go to the file: react.js/src/http.js
  - change variable BASE_URL to base url of your backend
  - adjust variables propertyDefinitionsUrl and proposalsUrl to use your backend endpoints if needed



# HOME WORK

## Design
![alt text](doc/images/image-6.png)

## Sign-in page (Live Page)
Login page:
![alt text](doc/images/image.png)
Filled fields on Login page:
![alt text](doc/images/image-1.png)
### Links from on Login page
![alt text](doc/images/image-2.png)
![alt text](doc/images/image-3.png)
### Success Logged to Backend API
![alt text](doc/images/image-4.png)
### Result from Backend API - Auth token
![alt text](doc/images/image-5.png)


### Code Solution

src\app\auth\pages\sign-in\
- sign-in.component.scss
- sign-in.component.html
- sign-in.component.ts


