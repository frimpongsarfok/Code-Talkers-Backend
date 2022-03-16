## STEPS TO INSTALL AND RUN

#set up db
1. docker ps -a
2. docker exec -it <post container id> bash 
3. psql -U <user name>
4. CREATE DATABASE code_talkers; 


  
#install app
1. npm install
2. npx knex  migrate:lastest
3. npx knex seed:run
4. npm start
 
