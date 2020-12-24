# WordPress Docker and Docker Compose Template

This is a yaml file to start a Development Environment using Wordpress and MySQL running in containers.

## Installation

Clone the repository to your project folder.

```bash
git clone https://github.com/fabioseidl/wordpress-docker-template.git
```

Navigate to the "wordpress-docker-template" folder and edit the docker-compose.yml file. Change the container name, plugin and theme folder with the name of your project. 

```bash
cd wordpress-docker-template
nano docker-compose.yml
```


Run the Docker Compose

```bash
docker-compose up -d
```

## How to Use

The webserver will start at port 80 in the container and mapped to the 80 port in yout localhost. Access this addres from you web browser and flow the steps to config the wordpress intalation.

The MySQL database can be accessed using a MySQL Client (like DBeaver) at the port 3306 in .

## License
[MIT](https://choosealicense.com/licenses/mit/)

