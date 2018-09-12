## Docker stack for Ruby on Rails configuration

# Services
- ruby (running ruby 2.5)
- mysql 5.6

# Configuration
Create .env file containing environmental variables which can be used in services configurations.

Format:

NAME_OF_VARIABLE=value

Currently supported:

- APP_NAME (Name of the app; Used for DB table name)
- MYSQL_USER
- ROOT_PASSWORD - password for mysql root user
- PASSWORD - password for ordinary DB user
- MYSQL_PORT 
