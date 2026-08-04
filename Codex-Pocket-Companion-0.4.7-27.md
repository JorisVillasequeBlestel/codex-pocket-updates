# Codex Pocket Companion 0.4.7

- Recharge aussi Codex Desktop lorsqu’aucune fenêtre ne possède encore la conversation, avec repli sûr après expiration du propriétaire précédent.
- Invalide le cache des tâches Codex et rouvre la conversation en arrière-plan au démarrage puis à la fin de la réponse.
- Décode correctement l’accusé de réception réel de Codex Desktop afin que l’iPhone confirme l’envoi sans faux échec ni nouvelle tentative en double.
- Envoie désormais le prompt de l’iPhone au propriétaire de la conversation déjà ouverte dans Codex Desktop : le message et la réponse apparaissent en direct sans fermer ni relancer Codex.
- Évite le double moteur Codex lorsque la conversation est visible et conserve un repli autonome lorsque Codex Desktop est fermé.
- Suit la fin des réponses lancées par la fenêtre Codex afin d’actualiser également l’iPhone.
- Conserve le canal de synchronisation strictement local et protégé par les permissions de l’utilisateur macOS.

- les conversations archivées sont maintenant exclues des listes et compteurs de projets sur iPhone ;
- les conversations créées depuis l’iPhone apparaissent désormais immédiatement dans Codex Desktop ;
- réparation automatique et sauvegardée des conversations mobiles déjà masquées par l’ancienne classification technique ;
- envoi fiable avec accusé de réception : le prompt n’est plus considéré comme envoyé avant l’acceptation de Codex ;
- ajout à l’agent actif avec `turn/steer`, sans échec lorsqu’une tâche est déjà en cours ;
- exposition dynamique des modèles, niveaux de raisonnement, compétences et apps disponibles sur le Mac ;
- prise en charge complète des questions et demandes de validation envoyées par Codex ;
- maintien du service 24/7, de la reconnexion automatique et de l’auto-réparation après une coupure ;
- conservation de l’authentification Bearer, des racines de travail autorisées et de la restriction au réseau Tailscale privé.
