```
npx djinit nodejs-postgres-restful-api-db
cd nodejs-postgre-restful-api-db
yarn add express body-parser sequelize pg pg-hstore
```

```
sudo service postgresql start
psql -d postgres -U db_user
mdp = "strongpassword123"
```

```
\c db_todo
\dt
```

```
SELECT * FROM users;

SELECT * FROM todos;

DROP TABLE users, todos;
```

```
postgres=> CREATE DATABASE db_todo;
postgres=> \q
```
