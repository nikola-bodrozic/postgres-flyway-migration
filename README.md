# Running migrations on database server using Flyway

Rename file `.env.default` to `.env` and place your PostgreSQL password.

Then

```shell
docker-compose up
```

in second terminal

```shell
docker exec -it pgdbserver bash
root@3244455842a2:/# psql -U postgres
postgres=# \c postgres
You are now connected to database "postgres" as user "postgres".
postgres=# select * from account;
 user_id | username
---------+----------
       1 | foo
(1 row)
```

