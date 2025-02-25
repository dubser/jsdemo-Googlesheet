Les boutons test.... ne servent pas.
Le bouton Authorize permet une Authentification Google 
interactive, à l'écran,afin de lire un fichier Xl logé sur un répertoire privé de
SDU. Les Crédentials sont dans un fichier private.js 
qui est .gitignore est est sauvegardé manuellement dans
githup/dubser/PrivateRepo
Pour s'autentifier sur google l'app doit provenir de
http://127.0.0.1:5500/  qui peut etre démarrée localement
avec : grelot:Googlesheet $ live-server --port=5500
Le login doit se faire sous dubser123
D'autres modes d'accès sont effectués avec node.js, voir
les examples avec les démos nodes.


Chiffrement pour les clefs API

https://www.npmjs.com/package/jsencrypt

TODO : Produire un script js qui lit en fichier
google sheet avec une app js sans demander de
connexion ni utiliser de ckef api.
