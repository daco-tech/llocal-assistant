# llocal-assistant
My SelfHosted Local Assistant

To run use: 

``` python
docker-compose up -d
```

Check status:

``` python
docker-compose logs -f 
```

Stop:

``` python
docker-compose down
```

Start from scratch:

Run: (note this commands will clean all your docker unused layers)

``` python
docker-compose down && docker system prune --all -f 
```

remove the two folders:

- ui-settings
- model_files

Then start again from scratch.
