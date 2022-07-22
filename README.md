# Tittle build an image through docker compose

# Requirements
	* Docker version 20.10.17, build 100c701
## About the repository

The proyect has
	Dockerfile
	docker-compose.yml
	index.html

in the sample the index.html was mounted like a file 
in the seccion volumes, you can try it with a template like:

	volmes:
	  - ./mytemplate:/var/www/html
 
## Sample Execution & Output

run the next command into the terminal
* docker compose up -d --build

	we can use the flag --build in the cases to create a image through a docker compose

check if the service is running with
* docker compose ps
checkt the new image was created with
* docker images

output it will be displayed: on the browser http://localhost:8099/

* This is a sample to create an image through docker compose file and create a container... by krlos 
