yarn add express
yarn add sucrase nodemon -D

"scripts": {
"dev": "nodemon src/server.js",
"dev:debug": "nodemon --inspect src/server.js"
},

nodemon.json
launch.json # debug

docker run --name some-postgres -e POSTGRES_PASSWORD=mysecretpassword -d postgres

systemctl start docker

INSERT do SQL => Create no Model (User.Create({}))

SELECT => findOne({where: {}})

yarn eslint init

.eslintrc.js

yarn add prettier eslint-config-prettier eslint-plugin-prettier -D

.prettierrc
.sequelizerc

yarn sequelize migration:create --name=create-users

yarn sequelize db:migrate
yarn sequelize db:migrate:undo // :all

yarn add bcryptjs
yarn add jsonwebtoken
yarn add yup
