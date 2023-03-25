Running Microsoft SQL Server in Docker.

Uses the [Microsoft SQL Server Docker image](https://hub.docker.com/_/microsoft-mssql-server).

# Run

Give read/write permission to user `mssql` (UID: 10001) on your data folder.
e.g. `sudo chown -R 10001 data`

Start: `docker-compose up`

Stop: Ctrl+c then `docker-compose down`

# Structure

Example parameters are set in the [.env](.env) file.
