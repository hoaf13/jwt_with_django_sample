# jwt_with_django_sample 

- POST: localhost/jwt/api  {"username":"" , "password":""} to get *access token* and *refresh token*
- POST: localhost/jwt/api/refresh {"username":"" , "password":""} to get new *access token*
- GET: localhost/jwt/hello/  + bearer Token (access token) to get response  