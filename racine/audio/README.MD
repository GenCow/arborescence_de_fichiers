## Contenu

La section audio (numérique) contient tout type de contenu sonore  - comme de la musique, des effets sonores, des podcasts, des livres audio, des enregistrements d'événements (comédies musicales, concerts, comédies stand-up), des jeux et bien d'autres.

Les types de fichiers les plus courants sont : `*.{raw,wav,flac,mp3,m4a,m4b,ogg,opus,aiff,aac}`

## Sous-sections

| Dossier      | Contenu                                                      |
| ------------ | ------------------------------------------------------------ |
| artistes     | artistes / groupes de musique                                |
| livres       | enregistrements de livres lus par une personne (aussi appelés livres audio) |
| compilations | collections de musique provenant de différents artistes / albums / événements |
| liste        | flux radio, playlists musicales, ..                          |
| podcasts     | émissions audio uniquement                                   |
| bandes_originales | contenu audio lié à d'autres médias comme les films, les émissions de télévision et les jeux vidéo |

## Patron

Le nommage des fichiers parmi les fichiers musicaux est un sujet très commun parmi les amateurs et il diffère beaucoup d'une personne à l'autre. Le fichier s’établit sur un modèle sur lequel beaucoup de gens s'entendent.

N'hésitez pas à créer vos propres modèles, en consultant les nombreux messages de forums spécialisés. Si vous voulez une introduction rapide, voici quelques modèles courants :

```
# + --------------------------------------------------------------------------------
# | Musique

# Un album classique avec un seul disque: %A - %T (%a) [%f]/%n - %t
ARTISTE/ARTISTE - ALBUM (ANNEE) [NUMERO]/NOMBRE_DE_PISTE - TITRE_DE_LA_PISTE

# Un album classique avec plusieurs disques: %A - %T (%a) [%f]/Disc %D/%n - %t
ARTISTE/ARTISTE - ALBUM (ANNEE) [NUMERO_DISQUE]/CD NUMERO/NOMBRE_DE_PISTE - TITRE_DE_LA_PISTE

# Un album de compilation sur un seul disque: %A - %T (%y) [%f]/%n - %a - %t
ALBUM_ARTISTE/ALBUM_ARTISTE - ALBUM (ANNEE) [NUMERO]/NOMBRE_DE_PISTE - ARTISTE - TITRE_DE_LA_PISTE

# Un album de compilation multi-disques: %A - %T (%y) [%f]/Disc %D/%n - %a - %t
ALBUM_ARTISTE/ALBUM_ARTISTE - ALBUM (ANNEE) [NUMERO_DISQUE]/CD [NUMERO]/NOMBRE_DE_PISTE - ARTISTE - TITRE_DE_LA_PISTE
# + --------------------------------------------------------------------------------

# + -------------------------------------------
# | TODO: Podcasts, Soundtracks, Playlists, ...
# + -------------------------------------------
```

## Resources

- https://musicbrainz.org/ - A community-maintained music metadata database.
- https://www.discogs.com/ - A database and marketplace for music.
- https://hydrogenaud.io/ - A community for discussion of audio technology.
- http://beets.io/ - A command-line based music tagger and cataloger.
