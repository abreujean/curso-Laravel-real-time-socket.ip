
## Procedimento de configuração

- Instalar laravel-echo-server
    laravel-echo-server init
    ? Do you want to run this server in development mode? Yes
    ? Which port would you like to serve from? 6001
    ? Which database would you like to use to store presence channel members? redis
    ? Enter the host of your Laravel authentication server. http://127.0.0.1:8000
    ? Will you be serving on http or https? http
    ? Do you want to generate a client ID/Key for HTTP API? Yes  
    ? Do you want to setup cross domain access to the API? Yes       
    ? Specify the URI that may access the API: http://127.0.0.1:8000
    ? Enter the HTTP methods that are allowed for CORS: GET, POST
    ? Enter the HTTP headers that are allowed for CORS: Origin, Content-Type, X-Auth-Token, X-Requested-With, Accept, Authorization, 
    X-CSRF-TOKEN, X-Socket-Id
    ? What do you want this config to be saved as? laravel-echo-server.json

    laravel-echo-server start

- Instalar redis

- Configurar redis
    foi necessario a instalação do predis
    Alterações feitas no arquivo config\app.php
    config\database.php 

- Configurar BROADCAST

 Alterações feitas no arquivo config\app.php
 alterações no .env

 - Instalar laravel-echo e socket.io-client para produção

 -Comando para subir as filas 
 php artisan queue:work