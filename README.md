# LocalDDBBExample

## Steps

### 1 -> Commands 1

npm init -y

npm install sequelize sqlite3 express swagger-ui-express
npm install -g sequelize-cli

npm install --save-dev sequelize-cli

npx sequelize-cli init

### 2 -> Express

app.js y etc

### 3 -> Swagger

swagger.json y etc

### 4 -> Commands 2

npx sequelize-cli model:generate --name User --attributes name:string,email:string,password:string

npx sequelize-cli db:migrate

### 5 -> Run and have fun/test

node app.js