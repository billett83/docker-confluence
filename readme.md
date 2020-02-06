# Docker - Confluence

Respoistory to build and run Confluence with Docker using an existing AWS RDS instance of PostgreSQl. This will run a basic single node instance of Confluence using HTTPS over port 8090.

## Configuration

### Container Variable

`ports` confluence UI port

### Tomcat Variables
------

`ATL_TOMCAT_SCHEME` https|http (default: http)
`ATL_TOMCAT_SECURE` true|false (default: false)

### Database Variables
------

`ATL_JDBC_URL` specific jdbc url for your chosen db
`ATL_JDBC_USER` db user
`ATL_JDBC_PASSWORD` db password
`ATL_DB_TYPE` postgresql|mysql|mssql|oracel12c
