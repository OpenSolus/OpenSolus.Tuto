Mémento Markdown
==================


Gestion des Titres
------------------

Titre niveau 1  

> ` Titre niveau 1 `  
> ` ================ ` 

Titre niveau 2  

> ` Titre niveau 2 `  
> ` --------------- ` 

Titre niveau 3 et plus  

> ` ###  Titre niveau 3 ###`  
> ` #### Titre niveau 4 ####` 

Ou version simplifiée

> ` ###  Titre niveau 3`  
> ` #### Titre niveau 4` 

---

Gestion des listes
------------------

Liste à puces avec - + * de la forme

    - puce 1
    - puce 2  
        - puce 2.1

Liste numérotée

    1. puce 1
    2. puce 2  
        1. puce 2.1  

---

Emphase du texte
----------------

**Gras**

>`**mot en gras**`

*Italique*

>`*mot en italique*`

~~Barré~~

>`~~mot barré~~`

`Code` (avec Alt Gr + 7)

> \`mot en code\`

ou 

> Tabulation sur au moins 2 lignes consécutives


Caractère d'échappement pour les caractères spéciaux reconnus par MarkDown

> `\`

---

Complément de texte
-------------------


Ligne de séparation

> `---`


Citation

> `>`

Retour à la ligne 

> Deux espaces à la fin de la ligne avant le retour chariot.

---

Les Liens
---------

Direct

> `<http://www.monlien.com>`

Texte 

> `[nom de mon lien](http://www.lien.com)`


Image : 

> `![Google logo](https://www.google.fr/images/srpr/logo11w.png "google logo")`

Le lien image fait directement apparaître l'image dans le document MarkDown. La partie entre "" sert à générer la balise `alt` et `title` de l'image affichée.

---

Les Tableaux
------------

Les tableaux générés avec MarkDown sont de la forme :

| Entête 1 | Entête 2  | Entête 3 |
|:--------|:---------:|---------:|
|coucou|c'est moi| le joli tableau|
| 12,34| 2,50 €| 1,50 $|

Et l'on doit les écrire 

>`| Entête 1 | Entête 2  | Entête 3 |`  
>`|:--------|:---------:|---------:|`  
>`|coucou|c'est moi| le joli tableau|`  
>`| 12,34| 2,50 €| 1,50 $|`  

La seconde ligne du tableau sert à configurer les alignements du contenu des colonnes.

Aligement à gauche
>`:----`

Alignement centré
>`:----:`

Aligement à droite
>`----:`

---

Sources :  

- <https://daringfireball.net/projects/markdown/syntax>  
- [Un guide pour bien commencer avec markdown](https://blog.wax-o.com/2014/04/tutoriel-un-guide-pour-bien-commencer-avec-markdown/)  
- <https://openclassrooms.com/courses/redigez-en-markdown>
- <https://help.github.com/articles/basic-writing-and-formatting-syntax/>

---

*[OpenSolus](https://opensolus.fr) &copy; mai 2018 - v1.4*
