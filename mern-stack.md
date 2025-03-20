# Screenshots of the EC2 instance setup 

## add images here
![mern1](mern1.PNG)
![mern2](mern2.PNG)
![mern3](mern3.PNG)
![mern4](mern4.PNG)
![mern5](mern5.PNG)
![mern6](mern6.PNG)
![mern7](mern7.PNG)
![mern8](mern8.PNG)
![mern9](mern9.PNG)
![mern10](mern10.PNG)
![mern11](mern11.PNG)
![mern12](mern12.PNG)
![mern13](mern13.PNG)
![mern14](mern14.PNG)
![mern15](mern15.PNG)
![mern16](mern16.PNG)
![mern17](mern17.PNG)
![mern18](mern18.PNG)
![mern19](mern19.PNG)
![mern20](mern20.PNG)
![mren21](mern21.PNG)

# Commands used for installation and configuration.

To install NVM (curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash)

then add this file docunment to load the NVM for use ( export NVM_DIR="$([ -z "${XDG_CONFIG_HOME-}" ] && printf %s "${HOME}/.nvm" || printf %s "${XDG_CONFIG_HOME}/nvm")"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh" )

install npm ( nvm install --lts)
check if node is installed( node -v)
check if npm is installed (npm -v )


mkdir
cd into the Dir
install npm express ( npm i express )
sudo nano into you ( sudo nano app.js )
then edit this into it to configure your application(const express = require("express");
const app = express();
const port = 5000;

app.get("/", (reg, res) => {
  res.send("hey, I am running and the port is " + port);
});

app.listen(port, () => {
  console.log("Server is running on port " + port);
});       )


install npm2 ( npm i -g pm2 ) ; this will make your application run in background even when you close your tab
install nginx ( sudo apt install nginx )
to start nginx (sudo systemctl start nginx )
to check if nginx is running ( sudo systemctl status )








# add URL for running the application
http://35.173.220.110/
