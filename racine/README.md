# racine

Le dossier racine définit le point d'entrée du support de stockage sur lequel il est utilisé.

Habituellement, les gens utilisent un disque externe, un partage réseau exposé par un NAS ou même des choses plus importantes comme les partages en cluster.

La **racine** définit plusieurs *sections principales*. Ces sections principales permettent une séparation facile du contenu et doivent rester dans une certaine complexité cognitive.

## Vue d'ensemble

| Dossier    | Contenu                                                      |
| ---------- | ------------------------------------------------------------ |
| adulte     | Contenu pour adulte est séparé dans son propre dossier.      |
| archives   | Sites Web, ensembles de données, sauvegardes et décharges, ...  |
| audio      | Musique, sons, balados, audio de jeux, ...                   |
| documents  | Documents personnels (factures, photos, sauvegardes, ..)     |
| images     | Art, photographie, fanart                                    |
| jeux       | Jeux de société, jeux de cartes, jeux vidéo, arcade, réalité virtuelle, ... |
| documentation | livres, écrits, documents scientifiques, articles, ...    |
| logiciel   | Logiciels, applications mobiles, systèmes d'exploitation     |
| vidéo      | Films, courts-métrages, émissions de télévision, ...         |



## Recommandations

Dans cette section, nous voulons vous donner quelques conseils généraux sur les choses que vous devriez savoir.

Ces conseils sont facultatifs et parfois biaisés. Si vous les rejetez - que ce soit partiellement ou complètement - ignorez cette partie.

### Nommer les fichiers et les dossiers

1. Nommer en général

Donner un nom est difficile. Nous le savons. Tout doit être propre et bien rangé, mais parfois les choses ne se passent pas ainsi - et c'est normal.  **N'ayez pas peur de briser les règles et d'ajuster cet arbre à vos besoins.**

2. Questions techniques

Certains systèmes n'autorisent tout simplement pas certains caractères, tandis que d'autres ne les utilisent pas correctement.

Voici une petite (et incomplète) liste de caractères à éviter (c.-à-d. "Caractères interdits")

- *Veuillez utiliser cette liste comme principe général.*
- *Cette liste s'applique à tous les systèmes d'exploitation*.


```
Séparateurs de fichiers :
: (deux points)
/ (barre oblique)
\ (barre oblique inversée alias "backslash")

Symboles non alphabétiques et non numériques :
¢ (Symbole des centimes)
™ (Symbole des marques de commerce)
$ (Signe du dollar)
® (Symbole de marque déposée)

Les signes de ponctuation, les parenthèses, les guillemets, les crochets et les opérateurs :
< (moins que)
> (plus que)
" (guillemets)
' (apostrophe)
| (bar vertical)
? (point d'interrogation)
* (astérisque)

D'autres " caractères " plutôt techniques :
Espace multiple ("Foo.      Bar   .txt")
Tabulation
Retour à la ligne
NUL (entier de valeur zéro)
Retours intégrés
```

Références:

- [Superuser StackExchange - How to create folder name with special characters?](https://superuser.com/a/1112140)
- [Superuser StackExchange - What are invalid characters for a file name under OS X?](https://superuser.com/questions/326103/what-are-invalid-characters-for-a-file-name-under-os-x)
- [StackOverflow - What characters are forbidden in Windows and Linux directory names?](https://stackoverflow.com/a/31976060)
