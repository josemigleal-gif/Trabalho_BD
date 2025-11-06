# Trabalho_BD
Sitema: Rede social com: Utilizadores, perfis, publicações, relações, comentários, mensagens, grupos, reações e publicidade 

São necessários os seguintes requisitos para a excução da rede de dados:

Um terminal ou ambiente de progamação para escrever comandos de SQL

PostGreSQL instalado (versão 13 ou superior)

  Estrutura de Ficheiros:
  
  BD2526_E1_Grupo02.zip
  
├── README.md

├── Tabelas.sql        (Criação de tabelas e restrições)

├── Triggers.sql       (Triggers de validação e automação)

├── Script.sql         (População da base de dados)

├── Functions.sql      (Stored procedures e functions)

├── Views.sql          (Views para relatórios)

└── Interrogações.sql  (Interrogações de teste)
 
Passos de exucução:

1. Criar a base de dados

CREATE DATABASE rede_social_bd;
\c rede_social_bd

2. Executar as Tabelas.sql

psql -U postgres -d rede_social_bd -f Tabelas.sql

3. Executar Triggers.sql

psql -U postgres -d rede_social_bd -f Triggers.sql

4. Executar data.sql

psql -U postgres -d rede_social_bd -f Script.sql

5. Executar Functions.sql
   
psql -U postgres -d rede_social_bd -f Functions.sql

6. Executar views.sql
   
psql -U postgres -d rede_social_bd -f Views.sql

7. Executar Interrogações.sql
    
psql -U postgres -d rede_social_bd -f Interrogações.sql
