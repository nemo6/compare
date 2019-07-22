# Lab

Télécharger le projet avec le bouton **Clone or download** puis **Download ZIP**.

Extraire le projet avec WinRAR : https://www.win-rar.com/start.html?L=10

Cliquer sur le fichier :

    compare_v2.html

Il suffit de glisser/déposer les deux autres fichers textes dans la zone grise.

**P.S**

Il y a bug avec 

```javascript
r1  = /.*\r\n/gi
```

Le regex séléctionne toutes les lignes suivie d'un saut de ligne (\r\n). Du coup, la toute dernière ligne du fichier n'est pas pris en compte.

