# devops-nginx
Создал такой конфиг [nginx.conf](https://github.com/bag2000/devops-nginx/blob/main/gateway/nginx.conf)  
  
Пытаюсь получить токен: 
```
curl -X POST -H 'Content-Type: application/json' -d '{"login":"bob", "password":"qwe123"}' http://localhost/token
```  
  
Получаю ответ:  
```
<html>
<head><title>502 Bad Gateway</title></head>
<body>
<center><h1>502 Bad Gateway</h1></center>
<hr><center>nginx/1.25.4</center>
</body>
</html>
```  
