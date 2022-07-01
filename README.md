# REST API made with Java and Spring Boot Framework

This is a simple REST API that connects to a database, allowing the user to create or select users already saved in the database. 

#### DB login:
~~~
user: root
password: 123456
~~~
You can change the login in application.properties file.

This API only has GET (/api/usuario/{code}) and POST (/api/usuario/salvar). Use the links mentioned in Postman. If you wish to save another user, you must send the message to the API in JSON, as shown below:

~~~json
{
  "codigo": 1,
  "nome": "Fernando",
  "login": "fernando",
  "senha": "123"
}
~~~
