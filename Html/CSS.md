**rel="stylesheet"** établit la relation entre la page et le fichier CSS.  
Ici, c'est une feuille de style (stylesheet, en anglais). Cet attribut est obligatoire, car la balise < link> sert également à plein d'autres choses, notamment à mettre en place des icônes de favoris (rel="favicon"),  des flux RSS (rel="alternate"), etc.  
  
**type="text/css"** établit le type de contenu.  
Ici, c'est un fichier texte, plus précisément de type CSS. Cet attribut n'est plus requis en HTML5, vous pouvez donc écrire  également **_< link rel="stylesheet" href="style.css">_**   
  
**href="style.css"** vous est déjà connu.  
Pour rappel, cet attribut précise le chemin vers le fichier CSS.


Vous pouvez utiliser les commentaires pour bien documenter votre feuille de styles CSS.  
  
Un commentaire se définit comme ceci :  
/* ceci est un commentaire css */  
Tout ce qui est compris entre /* et*/ est un commentaire, et est ignoré par les navigateurs.  Vous pouvez vous servir des commentaires pour mettre des annotations personnelles, des recommandations ou pour documenter votre code à l'attention du reste de votre équipe.  

  
Vous pouvez, par exemple, vous servir des commentaires pour indiquer à quelle partie les styles qui suivent sont destinés.  
  
**/* TEXTES */  
  
/* IMAGES */  
  
/* MENU */**  
  
etc.