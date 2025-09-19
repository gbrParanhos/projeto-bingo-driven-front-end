# bingo-driven
Sistema para a administração de jogos de bingo.

![demonstração do bingo](demo-bingo.gif)

## Funcionalidades
- Criação de jogos de bingo.
- Geração de números para um jogo (sorteio).
- Finalização de jogos.
- Armazenamento dos jogos e seus números sorteados.

## Links de Deploy
- Front-end: https://projeto-bingo-driven-front-end.vercel.app/

## Tecnologias
- Back-end: Node.js, Express, Typescript, Jest e Prisma.
- Banco de dados: Postgres.
- Front-end: React e Vite.

## Desenvolvimento
- Instalação:
  - Instalar as dependências com o `npm i`;
  - Criar o arquivo `.env` com base no exemplo do `.env.example`;
  - Executar o comando `npm run test`. 

## Uso com Docker
- Construir a imagem `docker build -t my-frontend .`.
- Rodar o front-end em um container docker `docker run -d --name my-frontend -p 8080:80 my-frontend`.

## Uso com Docker Compose
- Subir o container: `docker compose up -d`.
  