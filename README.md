inside 'src/config' folder create file named as 'config.json' and write following code inside it :
```
{
  "development": {
    "username": "root",
    "password": null,
    "database": "database_development",
    "host": "127.0.0.1",
    "dialect": "mysql"
  },
  "test": {
    "username": "root",
    "password": null,
    "database": "database_test",
    "host": "127.0.0.1",
    "dialect": "mysql"
  },
  "production": {
    "username": "root",
    "password": null,
    "database": "database_production",
    "host": "127.0.0.1",
    "dialect": "mysql"
  }
}
```
- If you are setting development environment, then write username and password of your DB and in dialect mention the database you are using such as mysql, mariaDB etc.

- If you are setting prod environment make sure to replace your host with the hosted DB url.