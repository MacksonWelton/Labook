# Labook

## Stack
Esse é um projeto de Backend feito utilizando NodeJS, Express, Typescript 
e MySQL. Além disso, ele segue uma arquitetura baseada em MVC, com 3 camadas 
simples:

1. Controller: responsável pela comunicação com agentes externos 
(como o Frontend)
1. Model: responsável pela representação das nossas entidades
1. Business: responsável pela lógica de negócio
1. Database: resposável por se comunicar diretamente com o banco de dados.

## Sobre

O LaBook é o back-end de uma rede social com o objetivo de promover a conexão e interação entre seus mais diversos usuários. Os usuários podem criar posts de dois tipos ("evento" ou "normal), comentá-los e curti-los também.

Conta com os seguintes endpoints.

1. Cadastrar
2. Logar
3. Fazer amizade
4. Desfazer Amizade
5. Criar post
6. Ver todo o Feed
7. Ver apenas um tipo de post do Feed

## Instruções para rodar
As instruções são:
1. `npm install` para instalar todas as dependências;
1. `npm run start` para rodar localmente o projeto
1. `npm run build` para gerar uma versão possível de ser deployada com 
os arquivos transpilados para Javascript
