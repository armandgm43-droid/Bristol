# Bristol

Fiches de révision à répétition espacée.

- `index.html` : le site.
- `cartes/index.json` : la liste des paquets à charger.
- `cartes/*.json` : un fichier par matière, contenu complet du paquet.

À chaque ouverture, le site lit ces fichiers et met à jour les paquets :
les cartes nouvelles sont ajoutées, les cartes modifiées sont mises à jour
sans perdre la progression, et les cartes retirées du fichier sont supprimées.

La progression est enregistrée dans le navigateur : elle est propre à
chaque appareil.
