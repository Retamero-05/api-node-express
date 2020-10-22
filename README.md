# Express + NodeJS
Nosso exemplo de API utilizando o Node com o Express

## Instalação do Express

```sh
$ npm init

$ npm install --save express

$ npm install --save sequelize

$ npm install -D sequelize-cli 

$ npm install --save mysql2

$ npx sequelize init 

```

config- configuração do banco de dados
migrations- alterações estruturais no banco de dados
models- faz referência a tabelas ano banco de ddos

##Criações de modelos e migrações

```sh

$ npx sequelize-cli model:generate --name=Client --attributes name:string,cpf:string,
email:string,phone:string,  

$ npx sequelize-cli db:migrate 

