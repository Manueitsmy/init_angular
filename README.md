# Angular start
### Mes premiers pas sur Angular


Afin de découvrir Angular, nous avons suivi un pas à pas dans le but de comprendre ses fonctionnalités.
Ce pas à pas se divise en 4 grandes parties :

Partie 1 - Initiation
 
Partie 2 - Routing Partie
   
Partie 3 - Data partie

Partie 4 - Formulaire

*******************************************************************************************************************************************************************************************

### **Partie 1 - Initiation**

Application qui parcourt les composants de données et de fonctionnalités qui comminquent entre eux.

* Créer l'exemple de projet

J'ai débuté avec un dossier contenant plusieurs fichiers.
Sur la page d'aperçu de l'application il y avait un en-tête ***"My Store"*** qui contenait le texte "My Store" et un bouton "Checkout".

* Créer la liste de produits

Grâce aux données déjà définies dans les fichier existants, j'ai fait appel à l'un d'eux afin d'afficher les différents téléphones.
La directive structurelle `*ngFor` m'a permis de créer dynamiquement dans le fichier product-list-component.html une liste grâce aux données définies dans le fichier products.ts

J'ai ensuite pu ajouter les descriptions. J'ai alors découvert le `*ngIf` qui indique une condition de type booléen qui ne renvoie que ce qui est vrai.

J'ai ajouté un bouton "Share" qui s'est ajouté sous chaque téléphone et qui renvoyait une fenêtre pop up.

***J'ai trouvé le côté dynamique apporté par Angular en très peu de lignes de codes très impressionnant et sympathique.***
  
* Transmettre des données à un composant

J'ai créé une nouvelle fonctionnalité d'alerte afin d'être prévenue si un téléphone côutait plus de 700$ à l'aide d'un bouton grâce auqel les clients peuvent s'inscrire pour être alerté.
J'ai tout d'abord généré un nouveau composant à l'aide du terminal de ce type :
```git
ng generate component product-alerts
```
***Cette fonctionnalité est géniale ! Je trouve que c'est un gain de temps et cela permet moins de prises de tête !***

* Transmettre des données à un composant parent


### **Partie 2 - Routing Partie**

* Assiocier une URL avec un composant

J'ai tout d'abord créé un nouveau fichier à l'aide du terminal :

```
ng generate component product-details
```

***Je suis toujours aussi impressionnée de voir que la création d'un composant avec une simple commande sur le terminal organise aussi bien les fichiers !***

J'ai ensuite ajouter un chemin vers le fichier généré par le terminal.

J'ai ensuite personnalisé l'élément d'encrage sur product-list.component.html à l'aide de la directive RouterLink ce qui peut me permettre de donner les détails de chaque téléphone en donnant un URL correspondant à l'ID donné.

***Toujours aussi dynamique !***

* Afficher les détails d'un produit

Avant d'afficher les détails des produits, j'ai effectué tout un processus grâce aux divers imports et diverses opérations qui m'ont amené à la page html où j'ai saisi les chemins jusqu'au fichier correspondant.

***Je n'ai pas tout à fait compris toutes les étapes jusqu'à l'affichage des détails...***

### **Partie 3 - Data partie**

* Définir un service de panier

J'ai tout d'abord définit un service de panier grâce au terminal avec la commande `cart` :

```
ng generate service cart
```

***J'ai été surprise de voir où se service s'est créé.***

J'ai ensuite importé l’interface depuis le fichier, et dans la classe, j'ai défini une propriété pour stocker le tableau des produits actuels dans le panier.

J'ai défini des méthodes pour ajouter des articles au panier, retourner des articles du panier et effacer les articles du panier.
  
* Utiliser le service de panier

  
* Créer la vue du panier


* Configurer le composant panier

  
* Afficher les articles du panier

  
* Récupérer les prix d’expédition

  
* Configurer pour utiliser AppModuleHttpClient

  
* Configurer pour utiliser CartServiceHttpClient

  
* Configurer pour obtenir les prix d’expéditionCartService

  
* Création d’un composant d’expédition

  
* Configuration de l’option à utiliser ShippingComponentCartService




### **Partie 4 - Formulaire**
