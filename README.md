# Musiz
Musiz est un lecteur musical basé sur une bibliothèque entièrement créée par l'utilisateur à partir de titres enregistrés localement ou disponibles sur le web. L'importation est aisée grâce à la lecture des métadonnées (utilisation de [jsmediatags](https://github.com/aadsm/jsmediatags)), et l'utilisateur peut personnaliser, pour chaque élément de la bibliothèque, le titre, l'artiste, le sous-titre/l'album, l'année, la pochette et les tags (qui permettent de classer et de trier les différents titres de la bibliothèque).

Attention : ceci n'est qu'un pour le moment qu'un début de projet tournant sous Electron. La seule langue actuellement disponible est le français

## Installation
```bash
# Cloner le répertoire
git clone https://github.com/Bouboufez/Musiz
# Aller dans le répertoire
cd Musiz
# Installer les dépendances
npm install
# Lancer l'application
npm start
```
Alternativement vous pouvez [télécharger le répertoire au format zip ici](https://github.com/Bouboufez/Musiz/archive/refs/heads/main.zip)

## Raccourcis clavier
| Touche  | Action |
| --- | --- |
| Espace  | Play/Pause  |
| Entrée | Passer au titre suivant |
| Flèches directionnelles gauche et droite  | Recul/Avance rapide  |
| Flèches directionnelles haut et bas  | Augmenter/Diminuer le volume  |
| M | Mute |
| L | Activer/désactiver la lecture en boucle |
| O | Diminuer la vitesse de lecture (minimum 20%) |
| P | Augmenter la vitesse de lecture |
| I | Lecture à vitesse normale (100%) |
| Echap. | Fermer le menu contextuel |
