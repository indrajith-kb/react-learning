
#How To Setup Your First React App

Prerequisites -You need to have nodejs installed on your machine. If you don’t, please go to https://nodejs.org and download the latest version. We need this because we use npm (node package manager) to manage all the dependencies and packages we use in our project.

##Using create-react-app command
#####. Simply create a directory on your local machine.
#####. Then Run the following commands.

npm install -g create-react-app

create-react-app my-app

cd my-app

npm start



##Something is already running on port 3000 ! why 

Just make an .env file at root of your project and add this line,

PORT=3002

and type 

npm start in cmd again.