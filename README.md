# boot-dev

Just a fast **booter** of an PHP-Apache2-Mariadb development environment with docker

### How to use ?

* Clone the project into your favorite folder
* Open your terminal and go to the folder that you have just cloned
* Just type :
    docker-compose up -d
* It will launch two containers
* Your project located to the "app" folder will be available at :
    localhost:8080
* Default credentials which connect to the database are : 
    MYSQL_ROOT_PASSWORD: root
    MYSQL_DATABASE: app
    MYSQL_USER: user
    MYSQL_PASSWORD: password
* You can edit it in the docker-compose file