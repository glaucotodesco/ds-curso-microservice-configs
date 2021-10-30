# ds-curso-microservice-configs

PgAdmin as a Docker:

  docker pull dpage/pgadmin4

  docker run -p 80:80 -e 'PGADMIN_DEFAULT_EMAIL=postgres@postgres.com' -e 'PGADMIN_DEFAULT_PASSWORD=1234567'  -d dpage/pgadmin4
  
  Inside de pgamin to connect with your DB, don't use localhost, instead use your IP.
  
