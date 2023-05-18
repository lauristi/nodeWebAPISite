# NodeWebAPISite

WebAPI feita em NodeJS que consome uma API externa
e usa render EJS para exibir os dados


A saber:

- Utiliza Swagger (swaager autogen) para gerenciar a documetacao
- Axios para acessar api externa que retorna as insrtituições bancarias do país
- Utiliza express no modelo MVC e Views com padrão EJS
- Utiliza Render EJS
- contem um certificado sef-signed e o codigo (comentado neste versão)


##### NOTAS

1 - Na pasta do projeto
```
npm init -y
```

2 - Instalacao basica:

```
npm install http express debug --save
```

##### Usando o gerador de aplicacao do express

```
1- npm install -g express-generator
```
Exemplo (cria uma aplicacao na Pasta NodeWebAPI):

```
     express -ejs -view=ejs -css --git NodeWebAPI
     npm install
     set DEBUG=myapp:* 
     npm start
```

##### Bibliotecas
```
npm install nodemon
npm install axios
npm install cors
npm install body-parser
npm install swagger-ui-express
npm install --save-dev swagger-autogen
```

