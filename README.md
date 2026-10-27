# CorpoSSH

CorpoSSH est une application de bureau pour se connecter en SSH et superviser des serveurs Linux. Elle réunit terminaux, transferts SFTP et tableau de bord, avec un mode kiosque pour afficher la supervision en continu.

## Télécharger

Les installateurs sont disponibles dans [Releases](https://github.com/SEIZURE-CORP/CorpoSSH/releases) : Windows x64 (`.exe`), Linux x64 (`.AppImage` ou `.deb`) et macOS Intel / Apple Silicon (`.dmg`). Choisissez le fichier correspondant à votre machine.

- **Windows** : lancez l'installateur et suivez les instructions.
- **Linux** : pour les mises à jour automatiques, rendez l'AppImage exécutable (`chmod +x CorpoSSH-*.AppImage`) et lancez-la depuis un dossier modifiable par votre utilisateur. Le paquet `.deb` se met à jour par votre méthode de déploiement habituelle.
- **macOS** : ouvrez le DMG et glissez CorpoSSH dans Applications.

CorpoSSH recherche les nouvelles versions publiées dans ce dépôt. En mode kiosque, sur Windows et en AppImage Linux, une mise à jour téléchargée est installée automatiquement et l'application redémarre dès que les terminaux et transferts sont terminés. Une connexion Internet est nécessaire pour les mises à jour ; l'utilisation SSH ne nécessite aucun service cloud.
