# Docker compose with MySQL and *phpmyadmin*

Database: https://www.mysqltutorial.org/mysql-sample-database.aspx

### Clone the repository
Use GitHub Desktop or the 'code' download button.

Instead from the terminal:
```
git clone https://github.com/Cryst4lDr4g0n/mysql-docker-eng.git
```

For Mac M* users uncomment  ```platform: linux/amd64``` in ```docker-compose.yml```

### Run
Install Docker https://docs.docker.com/get-docker/ and start containers from inside the *mysql-docker* folder:
```
docker-compose up -d
```

*sudo* may be required on Linux

```
sudo docker-compose up -d
```

To stop it:
```
docker-compose down
```
### Setting
**MySQL**: ```localhost:3306```

**phpmyadmin**: ```localhost:8081```

To verify the operation log in to *phpMyAdmin* and check for the presence of *classicmodels*.