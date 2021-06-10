$ npm install express-generator 
$ express api-usuarios
$ git init
$ git checkout-b main 
$ touch .gitignore 
npm i nodemon--save-dev


### Deixar o projeto rodando 
### Apagar as pastas 'public' e 'views';

### Ao apagas as pastas, não esqueça o codigo do arquivo 'app.js' o archivo  'src/routes/index.js';
arquivo 'app.js'
``` Javascript

### Definir a entidade de usuarios 
```Json 
{
"id": 
"nome": "Lila",
"email": "lilex82@gmail.com",
"telefone": "(11)992519227",
"senha": "123456", 
"status": true, 
}

### Definir endpoints da API usuarios
- Criar usuario      -[POST]'/usuarios'
- Listar usuarios    -[GET]'/usuarios'
- Busca um usuario   -[get]'/usuarios/:id'
- Atualizar usuario  -[PUT]'/usuarios/:id'
- Apagar usuario     -[DELETE]'/usuario/:id' 

C  - POST 
R  - GET 
U  - PUT/PATCH
D  - DELETE
