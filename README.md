# Reactive-resume

# Setup
create three folders in same path as the docker-compose file with the following names
minio_data
postgresql_data
redis_data

in the docker-compose.yml file for the app service replace the following ip address with your own
192.168.18.5

# execute
run docker-comppose up --build

# access
access the app at your <ip_address>:3030