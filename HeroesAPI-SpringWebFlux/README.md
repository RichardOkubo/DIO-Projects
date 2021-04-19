## API reativa com Spring Boot para gerenciar super heróis da Marvel e da DC

Pré-requisitos para a execução do projeto:

* Java 11 ou versões superiores
* Maven 3.6.3 ou versões superiores
* AWS CLI versão 2

_Stacks_ utilizadas:

- Spring Web Flux
- Spring Data
- DynamoDB
- Junit
- Sl4j
- Reactor

Para executar o _Dynamo_: 

``` shell script
java -Djava.library.path=./DynamoDBLocal_lib -jar DynamoDBLocal.jar -sharedDb
```

Depois, digite:

 ```shell script
aws dynamodb list-tables --endpoint-url http://localhost:8000
 ```

Para ver a documentação da API, veja no _Swagger_:

```url
http://localhost:8080/swagger-ui-heroes-reactive-api.html
```

