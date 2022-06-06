## open-telemetry-nodejs

### Requirements

- Node
- PostgreSQL
- Docker
- OpenTelemtry

### How to run

0. Run command `npm install`;
1. If using docker: `docker-compose up`;
2. Rename `.env.example` to `.env` and edit database environment variables;
3. Run `npm run sequelize:migrate` to create tables;
4. Run `npm run sequelize:seed` to create mock values in the database;
5. Run `npm run dev` to start the project using nodemon.
