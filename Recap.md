## Journal de bord

### 24/01/2024

Lors de la première réunion du projet, différentes stratégies pour la réalisation d'Akinator ont été présentées et discutées. Après délibération, l'équipe a décidé de concevoir un Akinator axé sur la devinette de Pokémon. La base de données sera dynamiquement enrichie, en comptant sur la contribution des utilisateurs pour étendre notre jeu de données.

La première étape consistera à ajouter manuellement quelques individus à la base de données. En cas d'absence d'un Pokémon dans la base de données, l'utilisateur sera invité à ajouter une question distinctive permettant de le différencier des Pokémon existants. L'attribut permettant cette distinction sera automatiquement ajouté à notre base de données, et une valeur de 1 sera attribuée à l'individu possédant cet attribut.

Pour les autres individus, la valeur de cet attribut ne sera pas encore définie. Cependant, elle sera déduite au fur et à mesure du processus. Si, lors d'une devinette, l'individu choisi n'est pas celui récemment ajouté mais que la nouvelle question est posée, la valeur de l'attribut sera attribuée en conséquence.

### 06/02/2024

Présentation d'une première méthode avec l'utilisation de la librairie python sklearn. Il reste des boîtes noir, notament concernant l'"indice de Gini", sa formule.

### 22/02/2024

Explication de l'indice de Gini lors de la réunion.

### Organisation

# un mini exemple sur une petite base de données

# un résumé de C5.0 et CART

# Overleaf

# petit résumé de gini et gain

L'indice de Gini d'après l'Insee, est un indicateur synthétique permettant de rendre compte du niveau d'inégalité pour une variable et sur une population donnée.

![Exemple arbre généré](image.png)

![Dataset](image-1.png)

Gini pour le premier noeud :

- différence des distances

  d1,2 = 1;
  d1,3 = 1;
  d2,3 = 0

- moyenne des distances

  md = 0,667

- moyenne des valeurs des individus

  M = 0,5

- Gini

  G = 0,667/(0,5\*2) = 0,667

Gini pour le second noeud :

- différence des distances :

  d2,3 = 1;

- moyenne des distances :

  md = 0,5

- moyenne des valeurs des individus

  M = 0,5

- Gini

  G = 0,5
