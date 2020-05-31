# Running migrations on database server using Flyway

docker-compose up

docker exec -it pgdbserver bash

psql -U postgres

\c postgres

select * from account;

SELECT * FROM schema_version;
