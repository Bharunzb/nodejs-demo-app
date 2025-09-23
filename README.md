### i have launched the instance with jey pair and security group with 22,80,3000 in security group rules. 
<img width="1913" height="1079" alt="Screenshot 2025-09-22 211116" src="https://github.com/user-attachments/assets/3c6ec72a-e6dc-414b-994b-a9efb94fcdfa" />
### and now connected to instance and installed docker,git and nodejs.
### now created server.js and package.json with basic code help of chatgpt. 
#### and now run that files npm install and npm start commands.
<img width="1918" height="1029" alt="Screenshot 2025-09-22 210530" src="https://github.com/user-attachments/assets/4cb07bc5-d140-436a-b0b3-686a64b7d2d8" />
### now created dockerfile.
<img width="1919" height="1040" alt="Screenshot 2025-09-22 210718" src="https://github.com/user-attachments/assets/3e4f695f-0d64-46ef-ad12-82bd24048ca1" />
### now build and run dockerfile with commands docker build -t nodejs.demo . and docker run -itd -p p 3000:3000 nodejs-demo.
<img width="1918" height="1029" alt="Screenshot 2025-09-22 210530" src="https://github.com/user-attachments/assets/7ea070c5-9c1f-4356-b65a-8e50912f896b" />
### now pushed the code to github and in dockerhub actions written in main.yml  to automate cicd when code pushes to git hub.
<img width="1916" height="1044" alt="Screenshot 2025-09-22 210607" src="https://github.com/user-attachments/assets/79e9027d-3277-4bbd-9d9a-9d32191363c6" />
<img width="1918" height="1050" alt="Screenshot 2025-09-22 210645" src="https://github.com/user-attachments/assets/2c86ee5e-2f8e-40df-8800-6df85c81c2b9" />
### now add docker hub credentials to github secrets.
### and now succesfully image pushed to dockerhub and application can accessed in localhost with port number 3000
<img width="1918" height="1056" alt="Screenshot 2025-09-22 210929" src="https://github.com/user-attachments/assets/782dc55b-6c82-4d2c-8e54-4b013e7bc9c8" />
