#DOCKER-COPMOSE BOOTSTRAP
##PHP7.4, nginx, postgres db, postgres test db

###start:
docker-compose up -d

###stop:
docker-compose down

### Enter db
psql -h localhost -p 54322 -U user -d pizza -W secret

### Enter test db
psql -h localhost -p 54323 -U user -d pizza -W secret
