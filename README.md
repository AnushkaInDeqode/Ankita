User Persistence Assignment in NodeJS and PostgreSQL
In this project we have used following dependencies

 node
 express
 sequelize
 babel
 cors
 eslint
 jest
 Cors
 dotenv
 bcryptjs
 cors
 joi
 nanoid
 pg
 swagger-ui-express
 docker
API End Points
Create User - POST : {url}/users
Get User - GET: {url}/users/{userId}
Get All Users - GET: {url}/users
Update User - PUT: {url}/users/{userId}
Delete User - DELETE: {url}/users/{userId}
Swagger Definition - GET: {url}/api-docs
Set NODE_ENV Variable (Windows)
SET NODE_ENV=development
Set NODE_ENV Variable (Linux)
export NODE_ENV=development
Install PostgreSQL
https://www.postgresql.org/download/

Add Dependencies
npm install || yarn
Start Server Windows
npm start || yarn start
Start Server Linux
npm run start:linux || yarn start:linux
ES Lint
yarn lint || npm run lint
Test with Jest
yarn jest || npm run jest
Test with mocha
yarn test || npm run test
Swagger Documentation
http://localhost:5000/api-docs
Postman collection :
File available in root directory with name (postman.json)
OR
Install Docker:
https://docs.docker.com/engine/install/

Install Docker compose:
https://docs.docker.com/compose/install/

Run With Docker Compose
docker-compose up -d
Swagger Documentation
http://localhost:5000/api-docs
Postman collection :
File available in root directory with name (postman.json)
##directory Structure

 |-src
 | |-config
 | | |-index.js
 | |-constants
 | | |-index.js
 | |-controllers
 | | |-index.js
 | | |-user
 | | | |-index.js
 | | | |-index.spec.js
 | |-configurations
 | | |-encrypt.js
 | |-models
 | | |-index.js
 | | |-user
 | | | |-index.js
 | |-routes
 | | |-index.js
 | | |-user
 | | | |-index.js
 | |-services
 | | |-index.js
 | | |-user
 | | | |-delete.js
 | | | |-get.js
 | | | |-post.js
 | | | |-put.js
 | |-validators
 | | |-index.js
 | | |-user
 | | | |-index.js
 |-stack.yml
 |-swagger.json
 |-yarn-error.log
 |-yarn.lock
 |-.babelrc
 |-.eslintrc.yml
 |-.gitignore
 |-app.js
 |-development.env
 |-Dockerfile
 |-jest.config.js
 |-package.json
 |-production.env
 |-README.md
Clear Docker :

sudo docker system prune -af
