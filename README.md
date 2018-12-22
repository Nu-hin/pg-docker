# docker-compose configuration to run PostgreSQL with PgAdmin4

## Usage:

1. Run `docker-compose up`;
2. Open [http://localhost:2080](http://localhost:2080);
3. Use `admin@localhost` as login and `0000` as password to log in to PgAdmin;
4. Add a new server:
	* server name: `postgresql`;
	* user name: `postgres`;
	* password: leave blank.

PostgreSQL data is stored in the project directory under `postgresql/data`.
PgAdmin data is stored in the project directory under under `pgadmin`.

