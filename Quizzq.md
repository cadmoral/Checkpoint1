## Qu'est ce qu’un navigateur ?

```
Un navigateur est une interface graphique qui est capable d'accèder à un réseau composé de différents serveurs. Le navigateur permet de 
demander et modifier l'information contenue dans les serveurs.
```

________________________________________________________________________________________

## Définissez l’ensemble HTML/CSS/JavaScript et leur utilités.


```
HTML est une structure composée d'hyperliens. HTML structure la composition des pages du navigateur. 
Le CSS est une feuille de style qui permet de configurer le format physique du contenu HTML comme par exemple la position des structures HTML, leur couleur, leur taille...
Javascript est un langage de programmation qui fournit des animations dans page HTML et il offre une plus grande variété d'intéractions 
entre l'utilisateur et le navigateur.
```
________________________________________________________________________________________


## Qu’est-ce qu’un élément HTML ? Un attribut ?

```

```
________________________________________________________________________________________


## Dans quels cas utilisez-vous des id au lieu des classes (et vice-versa) ?


```
J'utilise des id lorsqu'il s'avère nécessaire de distinguer l'élément HTML soit pour lui donner un style unique dans le CSS soit pour le désigner dans une fonction en Javascript. 

```
________________________________________________________________________________________


## Qu’est-ce que EcmaScript ?

```


```

________________________________________________________________________________________

## Pourquoi est-il important de bien indenter vos fichiers ?

```
Une bonne indentation est importante puisqu'elle permet de voir clairement la structure du code. 
```
________________________________________________________________________________________


## Quelle est la différence entre margin et padding ? 

```
Le margin crée de l'espace entre l'élément HTML dès l'extérieur et le padding le fait dès l'intérieur.


```

________________________________________________________________________________________


## Citez au moins 3 types de positionnement en CSS et expliquer leurs rôles.

```
Absolute: permet aux éléments d'occuper la première place de leur section.

Relative: les éléments occupent une place "relative", càd qu'ils se place en fonction de l'élément qui a une position absolute.
Inline: les éléments inline ont un comportement de texte.
Block: les éléments en block se comportent comme des divs.


```
________________________________________________________________________________________

## Qu’est-ce qu’une variable ?

```
Une variable est un élément défini à l'intérieur ou à l'extérier d'une fonction et qui peut être utilisé en tant que input. 
```
________________________________________________________________________________________


## Citez le plus de types JavaScript possible et définissez les rapidement.


```
STRING: c'est du texte
Number: nombres
Objet: groupe de texte et nombre

```
________________________________________________________________________________________


##  À quoi sert le mot-clef “if” ?

```

If permet de créer un fonction conditionnelle.


```

________________________________________________________________________________________

##  Définissez l’objet XHR en JavaScript, son abréviation. À quoi sert-il ?


```




```

________________________________________________________________________________________

## Qu’est-ce qu’une requête HTTP ? 

```
Un requête HTTP est une demande qui fait le navigateur lorsqu'il se connecte au serveur afin d'obtenir des informations tel que l'affichage de la page.
```
________________________________________________________________________________________


## Quelle sont les deux types de requêtes permettant de récupérer et d’envoyer de la donnée sur un serveur HTTP ?

```
GET 
POST

```

________________________________________________________________________________________

## À quoi sert le Header d’une requête ? Le “Content-Type” ?

```
Le Header d'une requête permet de connaître des information sur la connexion, le type de requête, et la réponse de la requête. 
```
________________________________________________________________________________________


## Donnez au moins 3 codes de réponse HTTP et définissez les.


```

200: réponse à HTTP GET
300: réponse de rédirection
400: réponse d'erreur d'addresse fait par l'utilisateur


```
________________________________________________________________________________________


## Définissez les rôles de Scrum Master et Product Owner.


```
Le Scrum Master est en charge de réaliser et de faire respecter les méthodes agiles du scrum.
Le Product Owner est en charge de représenter le client et ses besoins. Il produit les users stories et il propose celles à réaliser lors des sprints. 

```
________________________________________________________________________________________


## Citer 4 commandes utilisées avec GIT et expliquer leurs rôles.
```
Git commit -m"message": fait une capture du travail local avant.
Git push: le travail fait en local et qui est passé par un commit peut maintent rejoindre le repository remote.
Git checkout -b nomdelabranche: commande qui crée une brance et se place sur celle-ci.
Git add nomdufhicier: commande qui permet à git de prendre en compte le fichier afin de passer ensuite à commit ou à push.

```
________________________________________________________________________________________


## Expliquer le code suivant et indiquer le résultat retourné par la fonction.

```
function counter(){

        const sentence = "Validation de la première phase";

        const words = sentence.split(' ');

        let count = 0;


        for (let i = 0; i < words.length; i++) {
            var word = words[i];
            count += word.length;
        }
        return count;
}
```
```
Dans la fonction counter:
    On peut voir deux variables constantes : sentence et words. 
    Sentence est un string 
    Words est une deuxième fonction qui va réaliser un split sur la constante sentence.
    
    Il y a une autre variable count qui a pour valeur un nombre.

    La fonction counter est ensuite composée d'un for loop initialisé à zéro et qui finit lorsqu'il atteint la longueur de la variable word (càd le split de la constante sentence).
    La function détermine une autre variable word qui est définie comme la position de l'index dans la constante words. 
    Ensuite une dernière variable "count" est déterminée comme la longueur de la variable word.

    La fonction finit lorsqu'elle affiche la variable count. 

    La fonction counter compte le nombre de mots dans la constante sentence. 







```
________________________________________________________________________________________


## Algo 

Ecrire l’algorithme d’une fonction prenant en paramètre 2 arguments : le premier est une chaîne de caractère et le second correspondant au caractère recherché. Cette fonction retourne le nombre de fois que le caractère recherché est rencontré dans la chaîne de caractères.
Ex. 
   * chaîne : ‘examen’, caractère : ‘x’ => 1
   * chaîne : ‘wild code school’, caractère : ‘w’ => 1



```

let a = "stringstringcaracterecaracter";
let b = a.match(/c/g);


function checkpoint (Arg1,Arg2){

    let count = 0;

    for (let i = 0; i < b.length; i++){
    
        count = b.length;

    }
        console.log(count);
        return (count);
}

checkpoint (a, b);



```


