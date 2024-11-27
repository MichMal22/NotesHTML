**HTML sert à structurer, rendre compréhensible**

<ul>
<li>"<strong>br</strong>" = Back reset (retour à la ligne) / (C'est une balise orpheline)</li>
<li>"<strong>ol</strong>" = Ordered list (liste ordonnée)</li>
<li>"<strong>hr</strong>" = Horizontal ruler (ligne horizontale) / (C'est une balise orpheline)</li>
<li>"<span style="background-color: ..."> / </span> = Zone de texte en surbrillance / les 3 petits point = valeurs RGB</li>
<li>"<strong>ul</strong>" = Liste à puce (liste non ordonnées)</li>
<li>"<strong>h1 → h6</strong>" = Identification des titres</li>
<li>"<strong>p</strong>" = Paragraphe, il peut y en avoir autant qu'il ne le faut</li>
<li>"<strong>!-- commentaire --></strong>" = Code permettant d'insérer un commentaire. Uniquement visible dans le code source, les commentaires sont ignorés par les navigateurs durant le rendu de la page.</li>
<li>"<strong>header</strong>" = C'est une balise structurante qui définit un en-tête ("Head" signifie "tête" en anglais.) / à ne pas confondre avec "head"</li>
<li>"<strong>head</strong>" = C'est le conteneur pour les **métadonnées** et les fichiers de supports (CSS, JavaScript, etc.) de la page. Il est invisible aux internautes. / Il peut y en avoir qu'un seul par page HTML</li>
<li>"<strong>footer</strong>" = Définit le pied de page ou le pied d'une section de la page (de "foot" : "pied" en anglais). Elle définit du contenu qui se trouve généralement à la fin de la page ou d'une section de la page.</li>
<li>"<strong>img</strong>" = Insertion du image dans la page Web / la commande est suivie par "src" = la source de l'image / (base orpheline) </li>
<li>"<strong></strong>

</ul>
``Balise orpheline = n'a pas besoin d'être fermée

Par exemple :
```markup
<html>
<!-- Page modifiée par Eric le 25 mai 2018 -->
...
</html>
```
Les commentaires sont indispensable pour le travail en équipe, à retenir

`<meta charset="utf-8"> = Jeu de caractère permettant l'affichage de TOUT les caractères  (latins, cyrilliques, grecs, arabes, etc).

Avec UTF-8, tout va bien !

Sauf quand le serveur qui héberge la page codée en **UTF-8** utilise la norme **ISO-8859-1.**  

Cette norme qui définit les caractères pour l'Europe occidentale, appelée aussi **Latin-1,** regroupe les 191 caractères les plus utilisés en Europe occidentale.

Lorsqu'une page codée en UTF-8 est affichée par un serveur utilisant ISO-8859-1, on se retrouvera face à ce type d'affichage.

![[Pasted image 20240329223824.png]]

Pour résoudre cela, il suffit de changer le charset de la page (UTF-8) et de le définir comme ceci :

``<meta charset="iso-8859-1">

**Structurer un document HTML, c'est s'assurer :

- de sa visibilité : que le document soit correctement référencé par les moteurs de recherche,  
    
- de sa compatibilité : que le document soit correctement affiché dans les navigateurs,  
    
- de son accessibilité : que le document soit consultable par le plus grand nombre.

Le fichier image est un **fichier séparé du fichier HTML**


![[Pasted image 20240409101252.png]]