# Car_recommendation_system
Dialogflow

## TODO List (Windows)
- Make sure you have MySQL, Python, XAMPP, npm and ngrok installed in your PC
- cmd pip install pandas sklearn
- open XAMPP, start "Apache" and "Mysql" services
- git clone https://github.com/se7ven012/Car_recommendation_system.git
- cd Car_recommendation_system
- npm install npm node popper express jquery mysql bootstrap body-parser pm2 art-template express-art-template fs child_process
- Import "test.sql" to your database
- Import "CarsAI.zip" to your Dialogflow
- start ngrok, type "ngrok http 8080" and press ENTER
- Copy the HTTPS link to the Dialogflow agent that you imported just now (at Fulfillment), add "/carai" after the HTTPS link (Example: https://xxxxxxx.ngrok.io/carai)
- pm2 start app.js
- pm2 logs
- Access "localhost:8080" to test the system
