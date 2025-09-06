PHP JWT Authentication API
This project demonstrates how to implement JWT (JSON Web Token) authentication in PHP using the firebase/php-jwt
 library.

It includes:
login.php → Generates JWT after successful login.
profile.php → Verifies JWT before returning protected user data.
config.php → Stores secret key.

Features
1)Login with email & password.
2)Generate JWT tokens with expiry time.
3)Access protected routes with Authorization: Bearer <token>.
4)Token verification & error handling.
5)Works with Postman, frontend apps, or mobile apps.
