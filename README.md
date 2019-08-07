## How To Use

First you must replace the "ApiRestTraining" to your folder laravel project name on [default.conf](https://github.com/rudirahardian/laravel-env/blob/master/config/nginx/conf.d/default.conf).

and then run this command below inside this repo

```
docker-compose build

docker-compose up -d
```

After that done..

put your laravel project folder to the htdocs/

if you use mac

you must add on the off line host on /etc/hosts 
#host testing
127.0.0.1	testing.local

and the run on your browser http://testing.local/