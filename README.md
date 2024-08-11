# 	Plan.ner (Planejador de Viagens)

Este projeto faz parte do desafio da Next Level Week (NLW) Journey da Rocketseat

<strong> Descrição</strong>: Aplicação backend de um sistema de planejamento de viagens em grupo, o intuito é facilitar a comunicação entre as pessoas que irão viajar juntos podendo criar e visualizar as atividades que serão realizadas a cada dia da viagem, assim como links úteis que poderão ser utilizados pelo grupo no planejamento e decorrer da viagem.

### 🖥️ Tecnologias utilizadas

- Node.js
- Typescript
- Fastify
- SQLite
- Prisma
- Nodemailer (Envio de e-mails)
- Zod (Validação de dados de entrada da API)

### ⏯️ Passos para rodar o projeto

1. Clonar o projeto

   ```` 
   https://github.com/matheushardman/nodejs-trip-planner
   ````

2. Entre na pasta principal do projeto (desafio-tecnico-capyba) utilizando o CMD (Windows) ou Terminal (Linux/Mac)

   ```` 
   cd nodejs-trip-planner

3. Instale as dependências necessárias para rodar o projeto com o comando:

   ```` 
   npm install
   ````

4. Renomeie o arquivo .env-example para .env que contém as variáveis de ambiente

   ```` 
   cp .env-example .env ou copy .env-example .env
   ````

   Neste projeto estamos utilizando a porta 3333 para o backend

5. Execute o projeto

   ```` 
   npm run dev
   ````

6. Acesse http://localhost:3333/ para verificar se o servidor está ativo e funcional

Para visualizar os dados que estão no banco de dados SQLite você poderá executar o comando que irá abrir uma nova aba em seu navegador:

```` 
npx prisma studio
````
