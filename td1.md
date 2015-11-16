# TD1 :
envoyer à macha.dacosta@gmail.fr

Lister des requêtes possibles :

1) Pour GitHub : Parameters HTTP Redirects Authentication Rate Limiting Hypermedia

Pour la Météo : Météo par nom de ville Météo par id de ville Météo par coordonnées GPS Support Multi langues Température minimale/maximale dans le temps actuel

2) Choix de l'API Météo

3)get "http://api.openweathermap.org/data/2.5/weather?q=London&mode=html&appid=2de143494c0b295cca9337e1e96b00e0"
Access-Control-Allow-Credentials → true
Access-Control-Allow-Methods → GET, POST
Access-Control-Allow-Origin → *
Connection → keep-alive
Content-Type → text/html; charset=utf-8
Date → Mon, 16 Nov 2015 18:40:03 GMT
Server → openresty
Transfer-Encoding → chunked
X-Source → redis

4)post "http://api.openweathermap.org/data/2.5/weather?q=London&mode=html&appid=2de143494c0b295cca9337e1e96b00e0"
Access-Control-Allow-Credentials →
Access-Control-Allow-Credentials
Indicates whether or not the response to the request can be exposed when the credentials flag is true. When used as part of a response to a preflight request, this indicates whether or not the actual request can be made using credentials.
true
Access-Control-Allow-Methods → GET, POST
Access-Control-Allow-Origin → *
Connection → keep-alive
Content-Type → text/html; charset=utf-8
Date → Mon, 16 Nov 2015 18:41:24 GMT
Server → openresty
Transfer-Encoding → chunked
X-Source → redis

Tester les requêtes

1) La requête GET fonctionne

Conception Application Cliente

1) Permet de connaitre la température, le pourcentage d'ensoleillement, le pourcentage d'humidité, la vitesse du vent, la pression atmosphérique

2) ...

3) Mobile : https://ninjamock.com/s/BM98T Web : https://ninjamock.com/s/1M98T
