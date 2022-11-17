# EstoqueApi

### IMPORTANTE ###

 PARA PERFIL DEV:
    1. Criar schema do banco no mysql antes de rodar. CREATE SCHEMA estoque_api;
    2. Conferir se a senha é a mesma do seu mysql.
    3. Alterar propriedade ddl-auto para "spring.jpa.hibernate.ddl-auto:create".
    4. Rodar o projeto para hibernate criar as tabelas e inserir as informacoes do "import.sql".
    5. Voltar propriedade ddl-auto para "spring.jpa.hibernate.ddl-auto:none".

    OBS.: Se mantido o ddl-auto como create, o banco sera sobrescrito a cada execucao do projeto.

PARA PERFIL TEST:
    - O banco é criado automaticamente e dropado ao finalizar.

