# MongoDB - Aula 01 - Exercício
autor: Paulo Amorim

## Importando os restaurantes

    ```
    MacBook-Air-de-Paulo:mean paulo$ mongoimport --db be-mean --collection restaurantes --host localhost --drop --file restaurantes.json
    2016-05-22T12:11:47.802-0300	connected to: localhost
    2016-05-22T12:11:47.803-0300	dropping: be-mean.restaurantes
    2016-05-22T12:11:49.105-0300	imported 25359 documents

    ```

## Contando os restaurantes

    ```
    MacBook-Air-de-Paulo(mongod-3.2.6) be-mean> db.restaurantes.find({}).count()
    25359

    ```
