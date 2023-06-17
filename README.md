
# Imersão Full Stack && Full Cycle

Esse repositório contém o código-fonte  Nest.js + Server-Sent Events: Construindo Aplicações em Tempo Real

## 🚀 Rodar a aplicação

### express-sse

Acesse a pasta express-sse:

cd express-sse

Instale as dependências:

npm install

Para rodar a aplicação rode o comando:

npm run start

Acesse em seu navegador através do caminho: http://localhost:3000

### nestjs

Acesse a pasta nestjs:

cd nestjs

Rode os containers com o comando:

docker compose up

Entre no container do nest:

docker compose exec app bash

Instale as dependências:

npm install

Rode o comando para o prisma criar realizar a migrate:

npx prisma migrate dev

Para rodar a aplicação rode o comando:

npm run start:dev

Existe um arquivo na raiz do projeto Nest.js, o api.http que você pode usar para testar a aplicação com o plugin do VSCode REST Client. Quando enviar dados na requisição, o Nest.js consumirá a mensagem e mostrará no console.

## 🎉 Sobre o repositório

Este repositório é uma ótima fonte de informação para quem deseja aprender mais sobre Nest.js e server-sent events. Fique à vontade para explorar o código e aprender mais sobre essas tecnologias emocionantes!

## 📝 Licença

Este projeto está licenciado sob a licença MIT - consulte o arquivo LICENSE.md para obter detalhes.
