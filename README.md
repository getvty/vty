# Vty

Client SSH et console série pour switchs Cisco, pensé pour les équipes qui gèrent des centaines d'équipements.

**Site : https://getvty.com**

## Télécharger

[⬇ Vty 1.5.0 pour Windows](https://github.com/getvty/vty/releases/latest/download/Vty-setup.msi) · Windows 10 / 11 x64 · gratuit, Pro à 45 € HT

SHA-256 : `b2279df741aa22cd1fa78ed9a63eb44b3069bd92658e776ae27f7dc9ba5f2006`

Si Windows affiche « Windows a protégé votre ordinateur » : **Informations complémentaires → Exécuter quand même** (l'installeur n'est pas encore signé).

## Fonctions

- Garde-fous : reload, write erase, trunk sans `add`… interceptés avant l'envoi
- Multi-exec, écran partagé jusqu'à 4 terminaux, import CSV
- Sauvegardes des configs avec historique et comparaison
- Audit sécu noté de A à E (82 contrôles, CIS / DISA STIG / ANSSI)
- Failles connues via l'API Cisco PSIRT
- Commandes en masse en lecture seule, macros, SFTP / SCP avec MD5
- Aucun mot de passe enregistré, écoute uniquement en local

Ce dépôt contient le site et les versions publiées.
