### How to Access Prisma DB?

#### Up the docker container with this code in your terminal:

`docker compose up -d`

#### To create or update DB:

`npx prisma db push`

Always the DB Schema is changed, run the code below to generate the Updated Prisma Client.

`npx prisma generate`

#### Up the Prisma Studio do View the Database Data:

`npx prisma studio`

#### Access Prima Studio via the default port:

http://localhost:51212

#### Or set a new port:

`npx prisma studio --port 7777`
