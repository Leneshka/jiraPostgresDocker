Way to use:

1. Replace `database_user` and `<database_password>` in docker-compose.ym with actual values.
2. Run docker-compose.yml
3. Go to localhost:8080
4. Provide database credentials to initialize Jira's connection to it.
     *  Choose PostgreSQL as the database type.
     *  Database's host is available in docker; usually `172.18.0.2`, and port is `5432`.
     *  Database's name is `jira`.

Stopping both containers, deleting them and rerunning docker-compose.yml is a good way of troubleshooting.

dbconfig.xml is not used in this project. It was a part of attempt to better automate process,
but full automation is not possible due to the need of a license for Jira.


