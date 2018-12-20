# Évaluation individuelle

## Programmation - Coaching

```
Nom : 
Prénom : 
URL de votre compte Github : 
```

## Déroulé et fonctionnement. 

L'évaluation est à faire sur [Typora](https://typora.io/). Les réponses sont à écrire dans les blocks de code. 
Pour la partie Ruby, testez votre code sur [repl.it](https://repl.it/) et copiez le dans les blocks de code prévu à cet effet. 
Une fois fini, pushez votre feuille sur Github, dans un nouveau repository que vous appelerez "evaluation-inseec".
L'évaluation est individuelle et durera 1h30. Elle intègre des notions d'HTML, CSS, Ruby et computer science. 

![alt](https://media.giphy.com/media/26xBBfd0ii1khakpy/giphy.gif)

## Quelques mises en garde.

Je connais très bien ce merveilleux site qu'est Wikipédia. Je vous saurais gré de ne pas me remplir certaines questions avec les définitions de Wikipédia. Accessoirement, je sais aussi faire une recherche Google. Si j'ai un doute, je n'hésiterais pas rechercher "Qu'est-ce qu'une API" et comparer les définitions en tête de recherche avec les votre. Si je trouve une similarité trop grande et que je doute de votre bonne foi, je n'hésiterais pas à mettre 0 à la question. 
Pareil pour la copie sur les voisins. Si c'est trop gros et que j'ai un doute trop prononcé... 🔫

![alt](https://media.giphy.com/media/BtedgmzGNCiuk/giphy.gif)



------

### 1. Avec vos mots, expliquez l'interaction client-serveur

```t
L'interaction client-serveur c'est lorsqu'un programme (qui est le client) pose une question, fait une demande d'information à un autre programme (qui est le serveur). C'est sous la forme d'un échange de données.
```



 ### 2. HTML est un langage côté... 

```
Client 
```



### 3. Donnez-moi la structure de base d'une feuille HTML

```html
<!DOCTYPE html>
<!-- Completez après cette ligne -->
<html>
    
    <head>

    </head>
    
    <body>
        
    </body>
    
</html>
```



### 4. Changez la couleur du texte "J'adore la programmation" en rose en utilisant du CSS.

```html
<div>
    <style>
        p {color: red}
    </style>
   <p>J'adore la programmation</p>
</div>
```

```css
/* Ecrire le code CSS sous cette ligne */
<!DOCTYPE html>
<html>
  <div>
    <style>
        p {color: pink}
    </style>
   <p>J'adore la programmation</p>
</div>
</html>

```



### 5. Qu'est-ce que Bootstrap ?

```
Bootstrap est un site qui possède des outils nécessaires à la création de design de site et d'application web.
```



### 6. Reprenez votre code de la question 3 et ajoutez Bootstrap à votre feuille HTML, au bon endroit.

```html
<!DOCTYPE html>

<html>
    
    <head>

    </head>
    
    <body>
        <script src="bootstrap/js/bootstrap.min.js"></script>
    </body>
    
</html>

```



### 7. Mettez ces trois divs sur le même plan horizontal avec trois colonnes de même taille.

```html
<!DOCTYPE html>

<html>
    
    <head>

    </head>
    
    <body>
        <div>
            <div class="container">
                <div class="row">
                    Google
                </div>

<div>
    		<div class="container">
                <div class="row">
                    Microsoft
</div>

<div>
   			 <div class="container">
                <div class="row">
                    Apple
</div>
        <script src="bootstrap/js/bootstrap.min.js"></script>
    </body>
    
</html>

```



### 8. Avec le même code, changez le texte par le logo de la marque en question

```html
<!DOCTYPE html>

<html>
    
    <head>

    </head>
    
    <body>
        <div>
            <div class="container">
                <div class="row">
                     <img src="<img src="href="https://i1.wp.com/www.grapheine.com/wp-content/uploads/2015/09/nouveau-logo-google.gif?fit=1950%2C1200&quality=90&strip=all&ssl=1">
                </div>

<div>
    		<div class="container">
                <div class="row">
                  <img src="<img src="href="https://o.aolcdn.com/images/dims3/GLOB/legacy_thumbnail/630x315/format/jpg/quality/85/http%3A%2F%2Fi.huffpost.com%2Fgen%2F742825%2Fimages%2Fs-05370036PHOTOLOGOMICROSOFT2012-large640.jpg">
                    
</div>

<div>
   			 <div class="container">
                <div class="row">
                     <img src="<img src="href="http://www.lejournaldunumerique.com/wp-content/uploads/2012/03/Logo-Apple-Noir-Blanc.jpg">
</div>
        <script src="bootstrap/js/bootstrap.min.js"></script>
    </body>
    
</html>


```

 

### 9. Toujours sur le même bout de code, rendez les logos cliquables. Quand on clique sur le logo, on doit arriver sur le site officiel de la marque.

```html
<!DOCTYPE html>

<html>
    
    <head>

    </head>
    
    <body>
        <div>
            <div class="container">
                <div class="row">
                     <img src="<img src=href="https://i1.wp.com/www.grapheine.com/wp-content/uploads/2015/09/nouveau-logo-google.gif?fit=1950%2C1200&quality=90&strip=all&ssl=1"><href https://www.microsoft.com/fr-fr
                </div>

<div>
    		<div class="container">
                <div class="row">
                  <img src="<img src=href="https://o.aolcdn.com/images/dims3/GLOB/legacy_thumbnail/630x315/format/jpg/quality/85/http%3A%2F%2Fi.huffpost.com%2Fgen%2F742825%2Fimages%2Fs-05370036PHOTOLOGOMICROSOFT2012-large640.jpg"><href https://www.google.fr/
                    
</div>

<div>
   			 <div class="container">
                <div class="row">
                     <img src="<img src=href="http://www.lejournaldunumerique.com/wp-content/uploads/2012/03/Logo-Apple-Noir-Blanc.jpg"><href https://www.apple.com/fr/
</div>
        <script src="bootstrap/js/bootstrap.min.js"></script>
    </body>
    
</html>
```

![Mon gars sûr !](https://media.giphy.com/media/l0K4mbH4lKBhAPFU4/giphy.gif)

### 10. Parlons Ruby. Ruby est un langage côté...

```
Serveur
```



### 11. Listez-moi tous les types de données que vous connaissez.

```
String (chaine de caractère), Array, Boolean (true), Float (chiffre à virgule), Integer, Nil (absence), Num, Name, .each, .upcase, .downcase, == (égal à), != (différent de)
```



### 12. Assignez à des variables votre prénom, nom et le lien de votre compte Github puis affichez chacune des variables. En 6 lignes.

```ruby
first_name("Maeva")
last_name("Djoma")
```



### 13. Assignez 674 et 311 à des variables `a` et `b` et stockez le résultat `a` modulo `b` dans une variable `c` et affichez la. 

```ruby
a="674"
b="311"
c="52"
 puts  "#{a} x #{b}
# Le résultat attendu est 52. 
```



### 14. Qu'est-ce qu'une gem ? 

```texte
Une gem est un module de code crée par des developpeurs qui permet de donner des fonctionnalités supplémentaires à Ruby
```



### 15. Qu'est-ce qu'une API et qu'est-ce qui nous permet de nous y connecter ?

```
Une API (Application Programming Interface) est une interface pour les applications pour communiquer et échanger des données.
Pour se connecter il faut des clés d'API.
```



### 14. On va créer un script pour dire bonjour ou bonsoir, en fonction de l'heure de la journée. Votre script doit demander à l'utilisateur de rentrer son prénom. Si `hour` est inférieur à 12, lui dire `Bonjour Anthony` sinon `Bonsoir Anthony` (évidemment, le prénom doit être celui renseigné par l'utilisateur).

```Ruby
# <- Demander le prénom de l'utilisateur

Name="Maeva"
hour = 12

if < hour
    puts= "bonjour #{Name}"
if < hour 
    puts="Bonsoir #{Name}"
# Si hour est inférieur à 12
	# j'écris mon code permettant de dire Bonjour prénom
bonjour #{name}
# sinon
	# j'écris mon code permettant de dire Bonsoir prénom
bonsoir #{name}
```



### 15. Itérer sur l'array contenant des noms de twitos un peu famous et follow chacun d'eux grâce à une méthode trouvée dans la [doc de la gem twitter](https://github.com/sferik/twitter). Pas besoin de lancer le code et de faire la partie authentification. Juste le bloc d'itération suffira. 

```ruby
handles = ["@richardbranson", "@jeffweiner", "@LinkedInQueen", "@ericschmidt", "@elonmusk", "@petecashmore", "@SteveForbesCEO", "@mtbarra"]

client.update("I'm tweeting with @richardbrandson!")
client.follow("richardbrandson")
client.follow(213747670)


```



### 16. Félicitations, vous êtes arrivé·e à la fin, pushez cette feuille sur votre Github dans un repo appelé `evaluation-inseec`. N'oubliez pas de remplir le premier block avec votre identité tout en haut ! 

![alt](https://media.giphy.com/media/l0MYJnJQ4EiYLxvQ4/giphy.gif)

