## How To Use

First you must replace this name "ApiRestTraining" to your folder laravel project name on [default.conf](https://github.com/rudirahardian/laravel-env/blob/master/config/nginx/conf.d/default.conf).

and then run this command below inside this repo

```
docker-compose build

docker-compose up -d
```

After that done..

put your laravel project folder to the htdocs/

*if you use mac user
you must add on the end of line host on /etc/hosts 
*
```
#host testing
127.0.0.1	testing.local
```

if you use windows, or linux find the to change the host like that

and the run on your browser http://testing.local/

## work with cli on docker container
to get in on the bash container use command like this
```
docker exec -it {container_id} bash
```
