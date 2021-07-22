# GoStack-DesafioFinal

# - Backend

Na pasta backend, no arquivo .env.example basta inserir as chaves de acesso para o banco de dados, mailing, etc. (No desenvolvimento foi utlizado postgres, mongoDB e redis. tambem foi utilizado o mailtrap.io para realizar os testes de envio de email).

**OBS**: A url do mongo está no novo modelo. Ex: mongodb://url/nome_do_db.

*yarn migrate* - roda as migrations.

*yarn seed* - roda as seeds(No caso a seed que contem o admin user da aplicação).

*yarn dev* - inicia o backend.

*yarn queue* - inicia a fila do redis.

# - Frontend

*yarn start* - incia a aplicação.

# - Mobile

O app mobile foi desenvolvido e testado apenas no Android(a versão utilizada no desenvolvimento foi a 8.0.0).
