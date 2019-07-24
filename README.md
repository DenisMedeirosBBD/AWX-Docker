# AWX-Docker
This is a simple repository to deploy AWX using Docker.

Some notes:

- Change the variables *_PASSWORD to random passwords;
- Create a file `secret-key.txt` with a random password (it needs to be mapped as a volume).

To deploy it, just run:

``` 
$ docker-compose up -d 
```
