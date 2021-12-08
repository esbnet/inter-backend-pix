# Sistema em node e react que simula transação do PIX
## Requisitos e ambiente 

- Visual Studio Code
  Extensões:
- Insomnia ou Postman


---
## Techs

Node.js
Express
TypeORM
typescript -D
ts-node -D 
@types/express -D
@types/node -D
nodemon -D

Criando setup Ininical - Referencias.
https://dev.to/melquisedecfelipe/configurando-eslint-no-node-com-express-e-typescript-58p9

---
## Recursos nescessários na api - End-points

- Usuário
   - [x] Cadastrar novo usuário
   - [x] Efeturar login e retornar token de acesso

- PIX
   - [x] Efetuar solicitação de PIX
   - [x] Receber PIX
   - [x] Extrato
 
#### Regras: 
  - quando receber um pix, salvar na tabela de transação
