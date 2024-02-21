# MON CV EN HTML

Voici mon CV en HTML simple sans CSS. Dans le but d'avoir la structuration la plus claire et accessible.
La description qui suit, se fait dans l'ordre du code HTML afin d'expliquer les choix effectués. 

## HEAD

Dans le HEAD , l'ajout de `<title>` et `<meta name="description" .... >` pour rendre la page plus claire.

## BODY

### header
Dans le header on retrouve la navbar , avec chaque lien qui renvoi vers les sections du site tout comme on peut le visualiser avec HeadingsMap.

### main
Dans le main on retrouve en `<h1>` le titre implicite de la page et ce que l'on va y trouver ainsi qu'un `<p>` qui correspond au titre propre du CV

#### aside
La balise aside contient une image qui est la photo du candidat, expliqué avec un alt explicite

#### section
Les sections contiennent les divers parties principales du CV afin d'avoir un HTML plus structuré et accessible. 
1. Expériences
2. Formations
3. AutoFormations
4. Me contacter

Chaques sections contient en priorité un `<h2>` qui explicite le titre de la section. 
Par la suite on trouve les titres en `<h3>` de chaques expériences , formations, ect.. Afin d'avoir une hiérarchie logique.
Le contenu des h3 est suivi d'un H4 correspondant à la date généralement. Puis d'une liste pour explicité l'expérience, la formation ect...

##### Me contacter
On trouve dans cette section un form explicite celon les normes RGAA. Le form n'est cependant pas "fonctionnel" , pour cause d'un manque de connaissances des forms. 

### footer 

On trouve ici les contacts directement. 