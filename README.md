[Prerequisites]
docker installed on system.


The  `docker-compose.yml`  file is a simple configuration file telling docker compose which continers to build. That's pretty much it.


Now, to run containers based on the three images, simply run

```bash
$ docker-compose up
```


This will build the images if not already built, and run them. 
Once it's running, and your terminal looks something like this.


Reference:  https://scotch.io/tutorials/create-a-mean-app-with-angular-2-and-docker-compose