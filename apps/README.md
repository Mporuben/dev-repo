# Configure local code 



## API
1. run in `/apps`
    ```
    git clone https://github.com/Mporuben/web-api.git
    ```
2. copy configs from `docker-compose.override.example.yml` into `docker-compose.override.yml`
and uncomment `web` service 

3. run in root folder
    ```
    docker-compose run web npm i 
    ```


## FE App
1. run in `/apps`
    ```
    git clone https://github.com/Mporuben/web.git
    ```
2. copy configs from `docker-compose.override.example.yml` into `docker-compose.override.yml`
   and uncomment `web` service

3. run in root folder
    ```
    docker-compose run web npm i 
    ```
