# GABON 24 — Playlist IPTV

Playlist M3U pour regarder le direct GABON 24 dans VLC ou un lecteur IPTV compatible.

## Playlist

`GABON24.m3u`

Une fois ce dépôt public créé sous le compte `techservicespro`, avec le fichier sur la branche `main`, son adresse sera :

https://raw.githubusercontent.com/techservicespro/gabon24-iptv/main/GABON24.m3u

> Cette adresse ne sera accessible qu'après l'envoi des fichiers dans le dépôt GitHub public correspondant.

## Utilisation

- **VLC** : Média → Ouvrir un flux réseau → coller l'adresse Raw ci-dessus.
- **IPTV Smarters** : Ajouter une playlist → M3U URL → coller l'adresse Raw ci-dessus.

## Fonctionnement

La playlist GitHub pointe vers le serveur Northflank :

https://p01--gabon-24--4v7mhgcxbx8f.code.run

Vérification de l'état du serveur :

https://p01--gabon-24--4v7mhgcxbx8f.code.run/healthz

Le serveur extrait le direct depuis la page YouTube de GABON 24. Le démarrage peut prendre quelques secondes. La lecture dépend de la disponibilité du direct, de l'accès à YouTube et du fonctionnement du service Northflank. GitHub ne diffuse pas lui-même la vidéo.

## Mise à jour

Si l'adresse du serveur Northflank change, modifier uniquement la troisième ligne de `GABON24.m3u`, puis enregistrer le changement sur GitHub. Le lien Raw GitHub reste identique tant que le dépôt, la branche et le nom du fichier ne changent pas.

## Remarque

Usage personnel sous réserve des droits et conditions de diffusion de la chaîne et des plateformes concernées.
