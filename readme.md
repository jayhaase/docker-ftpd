#Managing the Container
Navigate to the directory containing the docker-compose.yml file to execute any of these commands:

- Starting: `docker-compose up -d`
- Stopping: `docker-compose down`
- View logs: `docker-compose logs -f`
- See what running: `docker-compose ps`

#Connecting to the FTP Server
Once the container is running, you will be able to connect to it with this command:
`ftp ftp://user:password@0.0.0.0`

#Volumes
This container uses two volumes:

- ./volumes/ftpuser/user : the FTP accessible directory
- ./volumes/pureftpd     : the configuration directory for Pure FTPD