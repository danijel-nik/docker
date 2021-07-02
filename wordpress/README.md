# Wordpress & Docker

To run this project locally (Wordpress, MySQL & PHPMyAdmin) just run this command:

```
$ docker-compose up -d
```

Go to PHPMyAdmin: ```http://localhost:8080/```

To see website: ```http://localhost:8000/```

Those ports can be changed in ``` docker-compose.yaml ``` file.

Keep in mind that if you run this project by first time, you will need to import database from ```_data``` directory. 

To Tear Down:

```
$ docker-compose down --volumes
``` 
