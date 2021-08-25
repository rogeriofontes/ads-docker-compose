# ads-docker-compose

docker run --name nossoapacha -p 8080:80 -v ./website/:/usr/local/apache2/htdocs/ httpd:2.4

docker stop nossoapacha 
docker rm tecmint-web
docker ps

docker image remove httpd:2.4
docker images


-----
docker-compose do postgres

para subir:

#docker-compose up -do
#docker-compose down


