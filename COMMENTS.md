Antes de mais nada obrigado pela oportunidade de participar do teste de vocês, agora sem mais delongas:

Utilizei uma arquitetura em camadas para o desenvolvimento

Bibliotecas utilizadas:
    jest -> para testes
    sequelize -> orm para auxiliar na manipulação de tabelas, rodar scripts, migrations, seeders 
    express -> framework para rotas
    ts-node-dev -> hotreload
    pg -> driver do postgress para trabalhar em conjunto com o sequelize
    dotenv -> controlar variaveis de ambiente
    ts-jest -> jest para type script
    supertest -> simular requisições http
    cors -> compartilhamento de recursos
    axios -> client http para requisições
    core-js -> biblioteca para js
    vuetify -> framework para layout, UI
    vue-router -> rotas

Melhorias caso houvesse mais tempo, adicionaria autenticação e todo processo envolvendo login e logout e tambem uma forma de exportar os dados da tela de alunos

Referente aos critérios obrigatórios quem não foram cumpridos creio que o ponto que mais deixou a desejar foi o commit mais organizado do código pro git


Comentário extra, subi a api e o banco no heroku para facilitar os testes do front e para os testes com o jest subi um outro banco para não afetar o fluxo principal, adicionar no .env na pasta student registration api code, ambos os bancos e api ficarão disponíveis até o final da avaliação

DATABASE_URL=postgres://vtafkgefoymdgk:a99908f8a2e169c8a74c3cfc6c58e23bba954c6615e05cc26a352ee290de4814@ec2-34-227-135-211.compute-1.amazonaws.com:5432/db5v5pngmm4hj5