i have launched the instance with jey pair and security group with 22,80,3000 in security group rules. 
and now connected to instance and installed docker,git and nodejs.
now created server.js and package.json with basic code help of chatgpt. 
and now run that files npm install and npm start commands. 
now created dockerfile.
now build and run dockerfile with commands docker build -t nodejs.demo . and docker run -itd -p p 3000:3000 nodejs-demo.
now pushed the code to github and in dockerhub actions written in main.yml  to automate cicd when code pushes to git hub.
now add docker hub credentials to github secrets.
and now succesfully image pushed to docjerhub and application can accessed in localhost with port number 3000
