# Continuité de GesComPro Lite

Le fichier `heartbeat.txt` est un « battement » signé, publié chaque jour par le serveur GesComPro.
Les applications GesComPro Lite le lisent : s'il a plus de 30 jours, elles cessent de bloquer les licences.

**Si plus personne ne gère GesComPro**, la personne de confiance remplace le contenu de `heartbeat.txt`
par le code de libération qui lui a été remis : toutes les applications se débloquent définitivement.

Ne pas supprimer ce dépôt.
