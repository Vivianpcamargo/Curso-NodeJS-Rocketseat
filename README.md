# :bookmark: Curso-Trilha-NodeJS-Rocketseat

:label: Tecnologia Principal: Typescript
<br> :bricks: Framework: Fastify
<br> :luggage: Banco de Dados: SQLite
<br> :page_facing_up: Padronização: ESLint
<br> :book: Documentação: <a href='https://www.figma.com/design/4S2uR1zvqbiT9ml8hSyaXl/NLW-Journey---Planejador-de-viagem?t=AjT8ZKsDrWOZgL8w-0'> Figma </a> e <a href='https://api.postman.com/collections/10550152-3854079d-6206-4dbd-b5e6-5cffd280d07e?access_key=PMAT-01J2Q5ZT3EB8JRM2TEKHD2SPWX'> Postman

## :dart: Sobre

O projeto é um site desktop para montar planos de viagem com amigos, registrar atividades e links úteis.

## :building_construction: Instalação do projeto

- instalar libs:
```
npm install
```

### :luggage: Acesso ao banco de dados

- visualizar no navegador:
```
npx prisma studio
```

#### :construction: Acesso ao drivers do SQLite

- criar o banco:
```
npx prisma init --datasource-provider SQLite
```

- criar tabelas:
```
npx prisma migrate dev
```

## :bar_chart: Rodando

### :test_tube: Exemplos de uso

- subir backend:
```
npm run dev
```

## :door: Portas do Projeto

#### :label: Backend

http://localhost:3333

`- trips`
* `GET /trips/:tripId`
* `PUT /trips/:tripId`
* `POST /trips`

`/confirm`
* `GET /trips/:tripId/confirm`

`/invites`
* `POST /trips/:tripId/invites`

`/activities`
* `GET /trips/:tripId/activities`
* `POST /trips/:tripId/activities`

`/links`
* `GET /trips/:tripId/links`
* `POST /trips/:tripId/links`

`/participants`
* `GET /trips/:tripId/participants`

`- participants`

`/confirm`
* `GET /participants/:participantId/confirm`

#### :label: Frontend

http://localhost:3000

#### :label: Banco de Dados

http://localhost:5555
