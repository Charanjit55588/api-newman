# api-newman

###Pre-requisite:
````
1. Node https://nodejs.org/en/download/
2. NMP  https://docs.npmjs.com/downloading-and-installing-node-js-and-npm
   npm install -g npm

You can verify the version of node and npm if you have already installed.
e.g. node -v, npm -v
````

###Steps to install Newman and Run:
````
1. npm install -g newman
2. Export your collection e.g. I have used Postman Echo project
3. newman run name_of_exported_json_file
````
or 


````
1. npm install -g newman
2. Clone the repository "https://github.com/Charanjit55588/api-newman.git"
3. newman run Postman\ Echo.postman_collection.json

All the tests will be executed in the terminal.
````
###Output/Report:

![](../../Desktop/Screenshot 2024-03-30 at 10.33.56 AM.png)
