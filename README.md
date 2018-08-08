# docker
Docker_containers


## wordpress
 - docker container : wordpress + mysql
 - docker-compose is used
 - please refer to docker-compose.yml
 - note that I used a volume mount mapping to a local host for the mysql data space
 - the volume mount mapping is as following : ./db_data ==> /var/lib/mysql
 - This means that data for wordpress will be stored at "./db_data" of the host
 - Althogh your containers are removed, you can recover them from that data of your host disk space.
 
 - run : docker-compose up -d
 
 ### TEST version 1.0 ###
 ### Branch version 1.1 ###
 
