**< form>< /form>**  
Balises délimitant un formulaire. Tous les champs et boutons appartenant à un même formulaire doivent se trouver dans cette balise.  
  
**method=" "**  
L'attribut de < form> qui permet de signaler au serveur de quelle manière sont passées les informations.  
Deux valeurs possibles : GET (valeur par défaut) ou POST.  
**  
action=" "**  
L'attribut de < form> qui permet de signaler au serveur l'adresse du script qui va traiter les informations encodées. Ce script est hébergé sur le serveur et écrit dans un langage de programmation tel que le PHP, l'ASP, ColdFusion etc.)  
  
**<input …**  
Balise qui permet d'insérer un champ dans un formulaire. Le type de champ (radio, text, checkbox, ..) est précisé dans l’attribut type.  
  
**type=" "**  
Un attribut de <input …> qui permet de préciser quel genre de champ sera présenté dans le navigateur.  
Voici les valeurs possibles : text, radio, checkbox, password, submit, reset, email, file, tel, date, range, button, color, url.  
  
**value=" "**  
C'est l'attribut qui définit la valeur du champ. Il est utile pour définir des valeurs par défaut par exemple.  
  
**< textarea>< /textarea>**  
Balise qui permet de disposer d'une zone de texte plus ou moins grande où l’utilisateur peut écrire un texte plutôt qu’une phrase.  
  
**< select>< /select>**  
Balise qui permet d'insérer une liste déroulante dans un formulaire.  
  
**< option>**  
Balise permettant d'ajouter une option dans une liste déroulante. Cette balise se trouve obligatoirement entre les balises < select>< /select>.  
  
**name=" "**  
Attribut qui s'applique à tous les champs et qui précise le nom d’un champ. Ce nom est utilisé par les scripts lors de la récupération des données.

**Notez que l'id est aussi fort sollicité par CSS et Javascript. C'est un attribut important des champs de formulaires, mais aussi pour tous les éléments HTML vus dans ce cours.**  
  
Id permet d'identifier chaque élément. Chaque élément ainsi identifié ne peut avoir qu'un nom exclusif au sein d'une même page HTML.  
  
**Exemples ;**  

-     < p id="texte">< /p>
-     < h1 id="livres">< /h1>
-     < br id="retours-section-1">
-     etc

  
**Pour récapituler ;**  
  
- l'attribut name définit le nom de la valeur (**la variable**) qui sera envoyée par le formulaire,  
- l'attribut **id** permet d'identifier l'élément html dans la page.