# docker-compose

### Docker Postgres (Database)

PostgreSQL database contains only single schema with two tables - kanban
and task table.

After running the app it can be accessible using these connectors:

- Host: *localhost*
- Database: *iotadb*
- User: *iotausr*
- Password: *iota*


Like other parts of application Postgres database is containerized and
the definition of its Docker container can be found in
*iota-docker-compose.yml* file.
