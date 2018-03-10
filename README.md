# android-php-login-registration  
## Fonte  
https://www.androidhive.info/2012/01/android-login-and-registration-with-php-mysql-and-sqlite/  
  
## Postman  
### Register  
http://localhost/android-login-api/register.php  
form-data  
name: Full Name  
email: email@com.com  
password: passwd  

Response:  
{"error":false,"uid":"5aa3b9c8912447.06258238","user":{"name":"Ful Name","email":"email@com.com","created_at":"2018-03-10 07:56:08","updated_at":null}}

### Login  
http://localhost/android-login-api/login.php
form-data  
email: email@com.com  
password: passwd  

Response:  
{"error":false,"uid":"5aa3b9c8912447.06258238","user":{"id":1,"name":"Full Name","email":"email@com.com","created_at":"2018-03-10 07:56:08","updated_at":null}}