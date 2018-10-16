Maintenance Philipp Kropp <philipp.kropp@gmail.com> 

Very basic example for WordPress using Docker
https://hub.docker.com/_/wordpress

dependencies: Docker must be installed

just clone repository

`git clone https://github.com/pkropp/docker-wordpress.git`

`cd docker-wordpress`


starting WordPress
#
`docker-compose up`
for stopping just use Ctrl + c
#
as demon (runs in background)

`docker-compose up -d`

for stopping
`docker-compose down`
in folder where you started docker-compose

License
----
MIT