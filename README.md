# deploy

## Variáveis de ambiente:

JDBC_DATABASE_URL: jdbc:postgresql://DB_HOST.oregon-postgres.render.com:5432/DB_NAME?sslmode=require

DB_USERNAME:
DB_PASSWORD:


# deploy_interface PASSO A PASSO

## ORIGINAL:

postgresql://db_conecta_user:p5MyQIVGHDSEZ2buoTLVeVmrbFW4V5sr@dpg-d0otki0dl3ps73aa9opg-a.oregon-postgres.render.com/db_conecta

PARA QUE A  SENHA DE DATABASE_URL ESTEJA ELEGÍVEL PARA SER UTILIZADA BASTA:

ADICIONAR AO INÍCIO >> 
jdbc:

APAGAR ESSE TRECHO >> 
db_conecta_user:p5MyQIVGHDSEZ2buoTLVeVmrbFW4V5sr@  (ESSE TRECHO FICA LOGO APÓS ÀS //)

DEPOIS DO .COM, ADICIONAR A PORTA:
5432

DEPOIS DO NOME DO BANCO DE DADOS, ADICIONAR >> 
?sslmode=require


## NOVO PASSWORD CRIADO A PARTIR DAS INSTRUÇOES PASSADAS ACIMA:

postgresql://dpg-d0otki0dl3ps73aa9opg-a.oregon-postgres.render.com:5432/db_conecta?sslmode=require






