# EmailVerification
Verificando usuarios enviando email para validar su sesion usando laravel 5.7


## Para utlizar el proyecto
1. Deben tener una cuenta de [Mailtrap](https://mailtrap.io/)

2. Modificar las credenciales en en ".env" de las siguiente manera:

* MAIL_DRIVER=smtp
* MAIL_HOST=smtp.mailtrap.io
* MAIL_PORT=2525
* MAIL_USERNAME='tuemail'
* MAIL_PASSWORD='tupassword'
* MAIL_ENCRYPTION=null

3. Configurar tu conexion a la base de datos en ".env"

4. por ultimo ejecutar las migracion php artisan:migrate
