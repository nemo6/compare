**P.S**

Il y a bug avec 

```javascript
r1  = /.*\r\n/gi
```

Le regex séléctionne toutes les lignes suivie d'un saut de ligne :

    \r\n 

Du coup la toute dernière ligne du fichier n'est pas pris en compte.
