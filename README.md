# Restpul-Api-Authentication-Single-Role
JavaScript - Restpul api authentication with JWT(JsonWebToken)

Tech Stack :
- Backend : Node.js, Express.js
- Database : Mysql
- Authentication : JWT (Json Web Token)
- Hash password : bcrypt
- Api Documentation : Swagger

how to install and running app :
- clone repo ""
- Active your database mysql
- creat new database in phpmyadmin named "authentication"
- export file database at folder Restpul-Api-Authentication-Single-Role/src/config/database/authentication.sql
- create file .env on folder Restpul-Api-Authentication-Single-Role, input
  APP_PORT=port
  DB_NAME=database_name
  DB_USERNAME=database_username
  DB_PASSWORD=database_password
  ACCESS_TOKEN_SECRET=random_string
  REFRESH_TOKEN_SECRET=random_string
- open folder Restpul-Api-Authentication-Single-Role with terminal input "npm install"
- run app "npm run dev"
