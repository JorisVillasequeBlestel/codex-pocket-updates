# Codex Pocket Companion 0.3.7

- reconnexion automatique persistante après une coupure, une relance ou une mise à jour ;
- temporisation progressive plafonnée à 30 secondes, sans alerte bloquante pour les coupures transitoires ;
- auto-réparation du service distant si l’application tourne mais que son port privé ne répond plus ;
- validation d’une mise à jour seulement lorsque le service distant écoute réellement ;
- installation différée tant qu’une session de contrôle entrante ou sortante est active ;
- conservation du chiffrement, de l’appairage et de la restriction au réseau Tailscale privé.
