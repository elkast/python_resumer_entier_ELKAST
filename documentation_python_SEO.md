## ######################################################################## Documentation Python pour étudiants TOUT NIVEAU ##################################################################


# Présentation du document
Ce document est une introduction complète et progressive à la programmation en Python, spécialement conçue pour les étudiants débutants ou de niveau intermédiaire, notamment en Sciences Économiques et Appliquées (SEA) Science Informatique (SI).
Il couvre les bases du langage, les principaux types de données, les opérations fondamentales, les structures de contrôle (boucles, conditions), la manipulation des collections, ainsi que des exercices pratiques et des quiz pour valider vos acquis.
L’objectif est de vous rendre autonome dans l’écriture de scripts Python simples et efficaces, indispensables pour l’analyse de données et la poursuite de vos études.

# Sommaire
Introduction à Python

Pourquoi apprendre Python ?

Installation et premiers pas

Les bases indispensables

Variables et types de données

Affectation et opérations

Exercices pratiques sur les variables

Les structures de données

Listes

Tuples

Dictionnaires

Ensembles

Exercices pratiques et quiz

Affectation et opérations

Affectation simple et multiple

Opérations arithmétiques

Incrémentation

Opérations sur chaînes de caractères

Quiz d’application

Les boucles en Python

Pourquoi utiliser les boucles ?

La boucle for (parcours de listes, tuples, dictionnaires, ensembles)

La boucle while (répéter tant qu’une condition est vraie)

Exercices et exemples concrets

Les fonctions

Définition et utilité

Passage de paramètres

Valeurs de retour

Fonctions avec *args et **kwargs

Fonctions imbriquées, lambda, récursives, génératrices

Exercices d’application

Quiz et sujets de synthèse

Quiz sur les types de données

Quiz sur les affectations et opérations

Sujet de projet complet (ex : gestionnaire d’élèves)


## #####################################################################################################################################################################################################################################################################################################################################################3####################
1. Introduction à Python
Python est un langage de programmation puissant, facile à apprendre, idéal pour l’analyse de données et la visualisation. Il est utilisé dans de nombreux domaines, notamment en économie pour traiter des données, automatiser des calculs et produire des graphiques.

2. Les bases indispensables
Variables et types de données

python
nom = "Alice"      # chaîne de caractères (str)
age = 20           # entier (int)
temperature = 22.5 # décimal (float)
actif = True       # booléen (bool)
Les principaux types sont : int, float, str, bool, ainsi que les structures comme list, tuple, dict, set.

# Exercices sur les variables et types de données
1. Déclaration et manipulation de variables
**Sujet 1** : Déclaration de variables
Déclarez les variables suivantes avec les types appropriés :

Un prénom (chaîne de caractères)

Un âge (entier)

Une température (nombre à virgule)

Un statut (booléen : actif/inactif)
Affichez le type de chaque variable à l’aide de la fonction type().

2. Conversion de type
**Sujet 2** : Conversion de variables
Soit la variable note = "17" (chaîne de caractères). Convertissez-la en entier.
Soit la variable prix = 15.99 (flottant). Convertissez-la en chaîne de caractères.

3. Opérations et concaténation
**Sujet 3** : Opérations et affichage
Créez deux variables entières x et y.
Affichez la somme, la différence, le produit et la division de ces deux variables.
Concaténez les valeurs de x et y dans une chaîne de caractères pour afficher le message :
"Les valeurs sont x = ... et y = ...".

Exercices sur les structures de données
4. Manipulation de listes
**Sujet 4** : Manipulation de listes
Créez une liste contenant les notes suivantes : 12, 15, 16, 10, 14.
Affichez la liste, puis calculez la moyenne des notes.
Ajoutez une nouvelle note à la liste et affichez à nouveau la liste.

5. Utilisation des tuples
**Sujet 5** : Création et accès à un tuple
Créez un tuple contenant le nom, le prénom et l’âge d’un étudiant.
Affichez chaque élément du tuple.

6. Manipulation des dictionnaires
**Sujet 6** : Création et accès à un dictionnaire
Créez un dictionnaire qui associe à chaque matière (clé) une note (valeur).
Ajoutez une nouvelle matière avec sa note.
Affichez la note d’une matière donnée.

7. Utilisation des ensembles
**Sujet 7** : Création et manipulation d’un ensemble
Créez un ensemble contenant les matières suivantes : "maths", "économie", "anglais".
Ajoutez une nouvelle matière à l’ensemble.
Affichez l’ensemble.

Exercice bonus
8. Échange de valeurs
**Sujet 8** : Échange de valeurs
Créez deux variables a et b.
Échangez leurs valeurs sans utiliser de variable temporaire (astuce Python possible).



# Affectation et opérations

**Qu’est-ce qu’une affectation en Python ?**
Une affectation consiste à associer une valeur à une variable en utilisant le symbole « = ». Cela permet de donner un nom à une information, de la stocker, puis de la réutiliser ou de la modifier plus tard dans le programme
Exercices sur l’affectation et les opérations

# Principe de base
Syntaxe :

python
**nom_variable = valeur**

Exemple :

python
age = 20
prenom = "Alice"

# Fonctionnement :
**Lors de l’affectation, Python crée la variable (si elle n’existe pas encore) et lui attribue la valeur indiquée à droite du signe " = "**


# Modification :
**On peut changer la valeur d’une variable à tout moment en réaffectant une nouvelle valeur :**
python
age = 20
age = 21  # La valeur de la variable age est maintenant 21

# Points importants
Le signe « = » n’est pas une égalité mathématique.
Il signifie « affecte la valeur de droite à la variable de gauche ».

# Sensibilité à la casse :
Les noms de variables sont sensibles à la casse : Prenom, prenom et PRENOM sont trois variables différentes.

# Affectation multiple :
**On peut affecter plusieurs variables en une seule ligne :**

python
x, y = 3, 4
**On peut aussi échanger les valeurs de deux variables facilement :**

python
a, b = b, a
Ce qui permute les valeurs de a et b.

# Affectation d’expressions :
**On peut affecter le résultat d’un calcul à une variable :

python
somme = 1961 + 58
Python évalue d’abord l’expression à droite, puis affecte le résultat à la variable

1. Affectation simple
**Sujet 1** : Affectation de valeurs
Déclarez deux variables, a et b, et affectez-leur respectivement les valeurs 5 et 3.
Affichez la valeur de chaque variable.

2. Réaffectation
**Sujet 2** : Réaffectation
Après avoir déclaré x = 4, réaffectez à x la valeur 1.
Affichez la valeur de x à chaque étape.

3. Affectation et copie
**Sujet 3** : Copie de variables
Déclarez a = 4 et b = 7.
Copiez la valeur de b dans a puis affichez les valeurs de a et b.
Refaites l’exercice en copiant la valeur de a dans b et observez le résultat.

4. Opérations arithmétiques
**Sujet 4** : Opérations de base
Déclarez deux variables entières x et y (par exemple, x = 10, y = 3).
Affichez le résultat de l’addition, la soustraction, la multiplication, la division, la division entière et le reste de la division entière (modulo) de ces deux variables.

5. Incrémentation
**Sujet 5** : Incrémentation
Déclarez une variable compteur = 0.
Incrémentez-la de 1, puis affichez sa valeur.
Utilisez ensuite l’opérateur += pour incrémenter compteur de 2, puis affichez sa valeur.

6. Opérations avec entrée utilisateur
**Sujet 6** : Lecture et opérations
Demandez à l’utilisateur de saisir deux nombres entiers.
Stockez-les dans des variables.
Affichez la somme, la différence, le produit et le quotient de ces deux nombres.

7. Échange de valeurs
**Sujet 7**: Échange de valeurs
Déclarez deux variables a et b avec des valeurs différentes.
Échangez leurs valeurs à l’aide d’une variable temporaire, puis affichez le résultat.
Essayez ensuite d’échanger les valeurs sans utiliser de variable temporaire (astuce Python possible).

8. Opérations sur chaînes
**Sujet 8** : Concaténation et réplication
Déclarez deux variables de type chaîne de caractères, par exemple nom = "Alice" et prenom = "Dupont".
Concaténez-les pour afficher le message complet.
Affichez le prénom trois fois de suite


## Quiz : Affectation et opérations en Python

### 1. **Affectation simple**

Quelle syntaxe permet d’affecter la valeur 10 à une variable nommée `x` ?  
A) `x == 10`  
B) `x = 10`  
C) `10 = x`  
D) `x := 10`  


### 2. **Modification de variable**

Après les lignes suivantes :  
```python
x = 4
x = 1
```
Quelle est la valeur de `x` à la fin ?  
A) 1  
B) 4  
C) 5  
D) Erreur  


### 3. **Affectation multiple**

Quel est le résultat du code suivant ?  
```python
a, b = 2, 3
print(a, b)
```
A) 2 2  
B) 3 2  
C) 2 3  
D) Erreur  


### 4. **Échange de valeurs**

Comment échanger les valeurs de `a` et `b` sans utiliser de variable temporaire ?  
A) `a = b; b = a`  
B) `a, b = b, a`  
C) `swap(a, b)`  
D) `a = b`  


### 5. **Opérations arithmétiques**

Quel opérateur permet de calculer le reste de la division entière ?  
A) `/`  
B) `//`  
C) `%`  
D) `**`  


### 6. **Incrémentation**

Après les lignes suivantes :  
```python
compteur = 0
compteur += 2
```
Quelle est la valeur de `compteur` ?  
A) 0  
B) 1  
C) 2  
D) 3  


### 7. **Opérations avec entrée utilisateur**

Que fait le code suivant ?  
```python
a = int(input("Entrez un nombre : "))
b = int(input("Entrez un autre nombre : "))
print(a + b)
```
A) Affiche la différence de deux nombres  
B) Affiche la somme de deux nombres  
C) Affiche le produit de deux nombres  
D) Affiche le quotient de deux nombres  

### 8. **Opérations sur chaînes**

Quel est le résultat du code suivant ?  
```python
nom = "Alice"
prenom = "Dupont"
print(nom + " " + prenom)
```
A) AliceDupont  
B) Alice Dupont  
C) Dupont Alice  
D) Erreur  

### 9. **Réplication de chaîne**

Quel est le résultat du code suivant ?  
```python
mot = "Python"
print(mot * 3)
```
A) PythonPythonPython  
B) Python3  
C) Python Python Python  
D) Erreur  

### 10. **Affectation d’expression**

Après la ligne suivante :  
```python
resultat = 5 * (2 + 3)
```
Quelle est la valeur de `resultat` ?  
A) 10  
B) 13  
C) 25  
D) 30  


## **Corrigé**

1. **B**  
2. **A**  
3. **C**  
4. **B**  
5. **C**  
6. **C**  
7. **B**  
8. **B**  
9. **A**  
10. **C**

## les types de doneés mieux expliquer 
voici une explication très claire sur les types de données **listes, tuples, dictionnaires et ensembles** en Python, avec des exemples concrets et sans autres notions compliquées letsgooooo!!!.


## Les types de données en Python

### 1. **Listes**

**Explication générale :**  
Une liste, c’est comme une boîte où tu ranges plusieurs objets differents. Tu peux ajouter, enlever ou changer les objets à tout moment.

**Exemple personnel :**  
Imagine que tu veux noter les prénoms de tes amis dans un carnet :  

```python
amis = ["Alice", "Bob", "Charlie"]
```
- **Ajouter un ami** :  
  ```python
  amis.append("David")
  ```
- **Enlever un ami** :  
  ```python
  amis.remove("Bob")
  ```
- **Afficher un ami** (par exemple, le premier) :  
  ```python
  print(amis[0])  # Affiche "Alice"
  ```


### 2. **Tuples**

**Explication générale :**  
Un tuple, c’est aussi une boîte, mais une fois qu’elle est fermée, tu ne peux plus rien y changer. C’est utile pour des données qui ne doivent pas être modifiées.

**Exemple personnel :**  
Tu veux noter les informations d’une personne (prénom, âge, ville) et tu ne veux pas que quelqu’un les change :  
```python
personne = ("Alice", 20, "Paris")
```
- **Afficher l’âge** :  
  ```python
  print(personne[1])  # Affiche 20
  ```
- **Tu ne peux pas modifier le tuple après sa création.**


### 3. **Dictionnaires**

**Explication générale :**  
Un dictionnaire, c’est comme un carnet où tu notes des mots et leur définition. Chaque mot (clé) a une définition (valeur). Tu peux toujours ajouter ou modifier des mots.

**Exemple personnel :**  
Tu veux noter les notes de tes matières :  
```python
notes = {"maths": 15, "anglais": 12, "histoire": 14}
```
- **Afficher la note de maths** :  
  ```python
  print(notes["maths"])  # Affiche 15
  ```
- **Ajouter une matière** :  
  ```python
  notes["français"] = 13
  ```
- **Changer une note** :  
  ```python
  notes["anglais"] = 16
  ```


### 4. **Ensembles**

**Explication générale :**  
Un ensemble, c’est comme un sac où tu ranges des objets, mais tu ne peux pas avoir deux fois le même objet. C’est utile pour garder une collection unique.

**Exemple personnel :**  
Tu veux noter les couleurs préférées de tes amis, sans doublons :  
```python
couleurs = {"rouge", "vert", "bleu"}
```
- **Ajouter une couleur** :  
  ```python
  couleurs.add("jaune")
  ```
- **Ajouter une couleur déjà présente** :  
  ```python
  couleurs.add("rouge")  # Ne change rien, "rouge" est déjà là
  ```
- **Afficher toutes les couleurs** :  
  ```python
  for couleur in couleurs:
      print(couleur)
  ```



## Résumé visuel

| Type         | Peut-on modifier ? | Peut-on avoir des doublons ? | Utilité principale                  |
|--------------|-------------------|-----------------------------|--------------------------------------|
| Liste        | Oui               | Oui                         | Ranger, modifier, ajouter, enlever   |
| Tuple        | Non               | Oui                         | Stocker des données fixes            |
| Dictionnaire | Oui               | Non (pour les clés)         | Associer une clé à une valeur        |
| Ensemble     | Oui (ajout/suppr) | Non                         | Garder des valeurs uniques           |



Avec ces exemples, tu comprends que chaque type de données a son utilité et sa façon de s’utiliser !  
Si tu veux, je peux te montrer comment les manipuler dans des situations réelles.


# sujet sur les types de donneé
## Quiz : Les types de données en Python


### 1. **Listes**

Quel code permet d’ajouter "David" à la liste `amis` ?  
```python
amis = ["Alice", "Bob", "Charlie"]
```
A) `amis.insert("David")`  
B) `amis.add("David")`  
C) `amis.append("David")`  
D) `amis += "David"`  


### 2. **Listes**

Comment accéder au premier élément d’une liste ?  
A) `liste`  
B) `liste`  
C) `liste.first()`  
D) `liste.get(0)`  


### 3. **Tuples**

Quel code définit correctement un tuple contenant le nom, l’âge et la ville d’une personne ?  
A) `personne = ["Alice", 20, "Paris"]`  
B) `personne = ("Alice", 20, "Paris")`  
C) `personne = {"Alice", 20, "Paris"}`  
D) `personne = {"nom": "Alice", "age": 20, "ville": "Paris"}`  


### 4. **Tuples**

Peut-on modifier un tuple après sa création ?  
A) Oui, toujours  
B) Non, jamais  
C) Seulement si on utilise une fonction spéciale  
D) Seulement pour ajouter des éléments  


### 5. **Dictionnaires**

Quel code permet d’afficher la note associée à "maths" dans le dictionnaire suivant ?  
```python
notes = {"maths": 15, "anglais": 12, "histoire": 14}
```
A) `print(notes["maths"])`  
B) `print(notes.maths)`  
C) `print(notes(0))`  
D) `print(notes["anglais"])`  


### 6. **Dictionnaires**

Comment ajouter une nouvelle matière avec sa note au dictionnaire `notes` ?  
A) `notes["français"] = 13`  
B) `notes.add("français", 13)`  
C) `notes.insert("français", 13)`  
D) `notes += {"français": 13}`  


### 7. **Ensembles**

Quel code permet d’ajouter "jaune" à l’ensemble `couleurs` ?  
```python
couleurs = {"rouge", "vert", "bleu"}
```
A) `couleurs.append("jaune")`  
B) `couleurs.add("jaune")`  
C) `couleurs["jaune"] = True`  
D) `couleurs.insert("jaune")`  


### 8. **Ensembles**

Que se passe-t-il si tu essaies d’ajouter "rouge" à un ensemble qui contient déjà "rouge" ?  
A) Une erreur se produit  
B) L’ensemble contiendra deux fois "rouge"  
C) L’ensemble ne change pas  
D) "rouge" est ajouté à la fin  


### 9. **Résumé**

Quel type de données permet d’associer une clé à une valeur ?  
A) Liste  
B) Tuple  
C) Dictionnaire  
D) Ensemble  


### 10. **Résumé**

Quel type de données garantit qu’il n’y a pas de doublons ?  
A) Liste  
B) Tuple  
C) Dictionnaire (pour les clés)  
D) Ensemble  

## **Corrigé**

1. **C**  
2. **B**  
3. **B**  
4. **B**  
5. **A**  
6. **A**  
7. **B**  
8. **C**  
9. **C**  
10. **D**

## ################################################################################# fin du quiz #########################################################################


# Les boucles en Python 

- Les boucles en Python (et dans la plupart des langages de programmation) sont utilisées principalement pour traiter des collections de données ou pour répéter des actions un certain nombre de fois.


## Sur quel type de donne utilisons nous des boucles ??
Excellente question !  
Les **boucles** en Python (et dans la plupart des langages de programmation) sont utilisées principalement pour traiter des **collections de données** ou pour **répéter des actions** un certain nombre de fois.  
Voici un aperçu des types de données et situations où tu utiliseras des boucles :

## 1. **Listes, tuples, dictionnaires, ensembles**

Ces structures permettent de stocker plusieurs valeurs.  
On utilise souvent des boucles pour **parcourir tous les éléments** et les manipuler un à un.

- **Liste** :  
  ```python
  notes = [12, 15, 16, 18]
  for note in notes:
      print(note)
  ```
- **Tuple** :  
  ```python
  eleves = ("Alice", "Bob", "Charlie")
  for eleve in eleves:
      print(eleve)
  ```
- **Dictionnaire** :  
  ```python
  matieres = {"maths": 15, "anglais": 12, "economie": 16}
  for matiere, note in matieres.items():
      print(matiere, ":", note)
  ```
- **Ensemble** :  
  ```python
  couleurs = {"rouge", "vert", "bleu"}
  for couleur in couleurs:
      print(couleur)
  ```


## 2. **Chaînes de caractères**

On peut utiliser une boucle pour **parcourir chaque caractère** d’une chaîne.

```python
mot = "Python"
for lettre in mot:
    print(lettre)
```


## 3. **Répéter un bloc un certain nombre de fois**

On peut utiliser une boucle `for` avec `range()` pour répéter une action un nombre précis de fois, même sans liste existante.

```python
for i in range(3):
    print("Bonjour")
```


## 4. **Tant qu’une condition est vraie**

La boucle `while` est utilisée quand on ne sait pas à l’avance combien de fois il faudra répéter une action.

```python
compteur = 0
while compteur < 5:
    print("Compteur :", compteur)
    compteur += 1
```

## **ce dont nous devons comprendre a ce niveau :**

On utilise des boucles avec des collections de donneé du type :
- **Listes, tuples, dictionnaires, ensembles** (pour traiter chaque élément)
- **Chaînes de caractères** (pour traiter chaque caractère)
- **Répétition d’actions** (avec `range()` ou une condition)


**En résumé :**  
Les boucles servent alors à traiter des collections de données ou à répéter des actions, quelle que soit la structure de données concernée !. vous n'avez pas bien compris **c'est pas grave a la suite vous comprendrez cela de manniere plus pertinent**


## Parlons des boucles en eux meme en Python mainitenant : 

Les **boucles** permettent de répéter plusieurs fois la même instruction ou le même bloc d’instructions.  
Elles sont très utiles pour éviter de répéter du code et pour traiter des listes de données, par exemple.

Il existe deux types principaux de boucles en Python :  
- **La boucle `for`**
- **La boucle `while`**



### 1. La boucle `for`

La boucle `for` sert à parcourir une séquence (comme une liste, un tuple, une chaîne de caractères, etc.) ou à répéter un bloc d’instructions un certain nombre de fois que nous connaissons bien sure a l avance.

**Exemple concret :**

Imaginons que tu veux saluer chaque élève d’une classe dans la liste suivante :
```python
eleves = ["Alice", "Bob", "Charlie"]
```
Tu peux utiliser une boucle `for` :
```python
for eleve in eleves:
    print("Bonjour", eleve)
```
**Résultat :**
```
Bonjour Alice
Bonjour Bob
Bonjour Charlie
```

**Autre exemple :**  
Compter jusqu’à 5 :
```python
for i in range(5):
    print(i)
```
**Résultat :**
```
0
1
2
3
4
```
(Note : `range(5)` génère les nombres de 0 à 4 inclus.)



### 2. La boucle `while`

La boucle while : quand et pourquoi l’utiliser
La boucle while permet de répéter un bloc d’instructions aussi longtemps qu’une condition reste vraie.

Quand utiliser while ?
On utilise la boucle while lorsqu’on ne connaît pas à l’avance le nombre de fois qu’il faudra répéter le bloc d’instructions.
Par exemple, tu veux demander à l’utilisateur de saisir un mot de passe tant qu’il n’a pas donné le bon, ou lire des données jusqu’à la fin d’un fichier.

**Astuce :**
Pense à la boucle while comme à un contrôle continu : on continue tant que la condition n’est pas remplie !

**Exemple concret :**

Imaginons que tu veux compter jusqu’à 3, mais avec une condition :
```python
compteur = 0
while compteur < 3:
    print("Je compte :", compteur)
    compteur = compteur + 1
```
**Résultat :**
```
Je compte : 0
Je compte : 1
Je compte : 2
```
Dès que `compteur` atteint 3, la condition `compteur < 3` n’est plus vraie, donc la boucle s’arrête.


## Ce qu'il faut retenir ici !!! 

- **`for`** : pour parcourir une séquence ou répéter un nombre précis de fois.
- **`while`** : pour répéter tant qu’une condition est vraie.
- **Indentation** : le bloc d’instructions à répéter doit être indenté (décalé vers la droite).
- **Utilité** : les boucles évitent de répéter du code et permettent de traiter facilement des listes ou des conditions répétitives.


**de manniere concret :**  
Essaie de visualiser la boucle comme un tour de manège : tu fais le tour tant que la musique joue (`while`), ou tu fais un nombre précis de tours (`for`).




## ########################################################## sujet de finn de section sur les boucles #################################################################
__

Bien sûr ! Voici un **sujet complet et bien rodé** qui permet de mettre en pratique tout ce qui a été vu sur les fonctions, les boucles, les types de données, les variables globales et locales, les arguments variables, etc. Ce sujet est idéal pour un projet de niveau débutant à intermédiaire en Python, adapté à des étudiants de L2 SEA ou tout autre niveau équivalent.

---

# **Sujet : Gestionnaire d’élèves et de notes**

## **Objectif**

Créer un programme qui permet de gérer une liste d’élèves, d’ajouter des informations (nom, âge, notes), de calculer des statistiques, d’afficher des résultats, et d’explorer toutes les notions vues sur les fonctions, les boucles, les variables et les collections de données.

---

## **Consignes détaillées**

### **1. Variables globales et locales**

- **Variable globale** : une liste qui contient tous les élèves.
- **Variables locales** : chaque fonction manipule des variables locales pour ses calculs.

### **2. Fonctions de base**

- **Ajouter un élève** : fonction qui prend un nom et un âge, et ajoute l’élève à la liste globale.
- **Afficher tous les élèves** : fonction qui affiche la liste des élèves.
- **Rechercher un élève** : fonction qui prend un nom et affiche l’élève correspondant.

### **3. Paramètres et arguments**

- **Fonction avec plusieurs paramètres** : ajouter un élève avec nom et âge.
- **Valeurs par défaut** : option pour ajouter un élève sans âge (par défaut, âge = 18).

### **4. Arguments variables (`*args` et `**kwargs`)**

- **Ajouter des notes à un élève** : fonction qui prend un nom et un nombre variable de notes (`*args`) et les ajoute à l’élève.
- **Afficher les informations** : fonction qui prend des arguments nommés (`**kwargs`) pour afficher des détails sur les élèves.

### **5. Fonctions imbriquées**

- **Calculer la note maximale** : fonction principale qui appelle une fonction imbriquée pour trouver la note la plus élevée d’un élève.

### **6. Fonctions lambda**

- **Trier les élèves par âge** : utiliser une fonction lambda pour trier la liste des élèves.

### **7. Fonctions récursives**

- **Compter le nombre d’élèves** : fonction récursive qui compte le nombre d’élèves dans la liste.

### **8. Fonctions génératrices**

- **Générer la liste des âges** : fonction génératrice qui retourne un à un les âges des élèves.

### **9. Boucles**

- **Utiliser des boucles `for`** pour parcourir la liste des élèves, afficher les informations, etc.
- **Utiliser des boucles `while`** pour demander à l’utilisateur de saisir des données jusqu’à ce qu’il décide d’arrêter.

Ce sujet te permettra de :

- **Manipuler des variables globales et locales**
- **Utiliser tous les types de paramètres et d’arguments**
- **Mettre en œuvre des fonctions imbriquées, lambda, récursives, génératrices**
- **Utiliser des boucles `for` et `while`**
- **Afficher, rechercher, trier et calculer des statistiques**

## correction


## ####################################################################################fin du sujet


# Une Fonctions en python c est quoi ? 

Bien sûr tout les etudiants ont peur des fonction mais c'est juste un mythe, voici un guide détaillé et exhaustif sur toutes les formes d’utilisation des fonctions en Python, avec explications et exemples concrets vous verez que nous utilisonsles fonctions  tout les jours sans le savoir.

## 1. **Définition d’une fonction en python**

Pour créer une fonction, on utilise le mot-clé `def` suivi du nom de la fonction, de parenthèses (pour les paramètres) et d’un deux-points. Le corps de la fonction est indenté.

```python
def saluer():
    print("Bonjour !")
```


## 2. **Appel d’une fonction**

Pour utiliser la fonction, il suffit d’écrire son nom suivi de parenthèses.

```python
saluer()  # Affiche "Bonjour !"
```


## 3. **Fonction avec paramètres**

On peut passer des informations à la fonction grâce à des paramètres.

```python
def saluer(nom):
    print("Bonjour", nom)

saluer("Alice")  # Affiche "Bonjour Alice"
```


## 4. **Plusieurs paramètres**

On peut avoir plusieurs paramètres, séparés par des virgules.

```python
def saluer(nom, age):
    print("Bonjour", nom, "tu as", age, "ans")

saluer("Bob", 22)  # Affiche "Bonjour Bob tu as 22 ans"
```


## 5. **Paramètres par position et par mot-clé**

- **Par position** : l’ordre des arguments correspond à l’ordre des paramètres.
  ```python
  def afficher(a, b, c):
      print(a, b, c)

  afficher(1, 2, 3)  # Affiche 1 2 3
  ```
- **Par mot-clé** : on précise le nom du paramètre lors de l’appel.
  ```python
  afficher(b=2, a=1, c=3)  # Affiche 1 2 3
  ```


## 6. **Valeurs par défaut des paramètres**

On peut donner une valeur par défaut à un paramètre, qui sera utilisée si aucun argument n’est fourni.

```python
def saluer(nom="inconnu"):
    print("Bonjour", nom)

saluer()         # Affiche "Bonjour inconnu"
saluer("Alice")  # Affiche "Bonjour Alice"
```


## 7. **Fonction qui retourne une valeur**

On utilise le mot-clé `return` pour renvoyer un résultat.

```python
def calculer_somme(a, b):
    return a + b

resultat = calculer_somme(5, 7)
print(resultat)  # Affiche 12
```

## 8. **Retourner plusieurs valeurs**

On peut retourner plusieurs valeurs sous forme de tuple.

```python
def operations(a, b):
    return a + b, a - b

somme, difference = operations(10, 3)
print(somme)       # Affiche 13
print(difference)  # Affiche 7
```



## 9. **Fonction sans paramètre ni retour**

C’est une fonction qui ne prend rien et ne retourne rien, mais qui peut afficher ou modifier des variables globales.

# bon affaire de global si j explique pas je voir deja des cadavres 

**global & local c est quoi meme ? :**
Pense à la variable globale comme à un objet dans une pièce commune : tout le monde peut le voir et l’utiliser.
La variable locale, c’est comme un objet dans une boîte : seule la personne qui a la boîte (la fonction) peut l’utiliser.
Globale = accessible partout.
Locale = accessible seulement dans la fonction où elle a été créée.

**Exemple:**
```python
def afficher():
    y = 5  # y est une variable locale parcequ'il est appeler a l interieur d une fonction
    print(y)  # On peut utiliser y ici

afficher()  # Affiche 5
print(y)    # ERREUR : y n'existe pas ici, cherche pourquoi c 'est ton petit quiz
```

## revenons a l'utilisation de nos fonctions sans paramètre ni retour

```python
def afficher_message():
    print("Ceci est un message")

afficher_message()  # Affiche "Ceci est un message"
```


## 10. **Fonction avec un nombre variable d’arguments**

On peut accepter un nombre variable d’arguments avec `*args` (pour les arguments positionnels) ou `**kwargs` (pour les arguments par mot-clé).


**Astuce :**
*args = tu donnes plusieurs valeurs, la fonction les reçoit toutes.il est plus utiliserpour passer plein d’arguments sans nom avec les fonctions , ou autre types de donneé en python.

**kwargs** = tu donnes plusieurs valeurs avec un nom, la fonction les reçoit toutes avec leur nom. donc lui c est  pour passer plein d’arguments avec un nom. **tellement simple ?**


```python
def afficher_tout(*args):
    for arg in args:
        print(arg)

afficher_tout(1, 2, 3)  # Affiche 1, 2, 3
```

```python
def afficher_mots(**kwargs):
    for cle, valeur in kwargs.items():
        print(cle, ":", valeur)

afficher_mots(a=1, b=2)  # Affiche a : 1, b : 2
```


## 11. **Fonctions imbriquées**

On peut définir une fonction à l’intérieur d’une autre fonction.

```python
def calculer(a, b):
    def multiplier(x, y):
        return x * y
    return multiplier(a, b)

print(calculer(3, 4))  # Affiche 12
```

## 12. **Fonctions lambda (fonctions anonymes)**

Les fonctions lambda sont des fonctions anonymes, souvent utilisées pour des opérations simples.

```python
somme = lambda a, b: a + b
print(somme(2, 3))  # Affiche 5
```


## 13. **Fonctions récursives**

Une fonction peut s’appeler elle-même.

```python
def factorielle(n):
    if n == 0:
        return 1
    else:
        return n * factorielle(n - 1)

print(factorielle(5))  # Affiche 120
```


## 14. **Fonctions comme objets**

En Python, les fonctions sont des objets. On peut donc les stocker dans des variables, les passer en argument ou les retourner.

```python
def saluer(nom):
    print("Bonjour", nom)

fonction = saluer
fonction("Alice")  # Affiche "Bonjour Alice"
```


## 15. **Fonctions génératrices**

Une fonction génératrice utilise le mot-clé `yield` pour retourner des valeurs une par une.

```python
def nombres_pairs(n):
    for i in range(n):
        if i % 2 == 0:
            yield i

for x in nombres_pairs(10):
    print(x)  # Affiche 0, 2, 4, 6, 8
```

## 16. **Fonctions natives et importées**

Python propose de nombreuses fonctions natives (comme `print`, `len`, `type`[1][8]), et on peut aussi importer des fonctions depuis des modules.

```python
import math
print(math.sqrt(16))  # Affiche 4.0
```


## Résumé visuel

| Forme d’utilisation           | Description/Exemple                                         |
|-------------------------------|------------------------------------------------------------|
| Définition                    | `def f(): ...`                                             |
| Appel                         | `f()`                                                      |
| Paramètres                    | `def f(a, b): ...`                                         |
| Valeurs par défaut            | `def f(a=1): ...`                                          |
| Retour                        | `return ...`                                               |
| Plusieurs retours             | `return a, b`                                              |
| Arguments variables           | `*args`, `**kwargs`                                        |
| Fonctions imbriquées          | `def f(): def g(): ...`                                    |
| Fonctions lambda              | `lambda a, b: a + b`                                       |
| Fonctions récursives          | `def f(n): ... f(n-1) ...`                                 |
| Fonctions comme objets        | `fonction = f`                                             |
| Fonctions génératrices        | `def f(): yield ...`                                       |
| Fonctions natives/importées   | `print`, `math.sqrt`                                       |


## Explication détaillée de l’utilisation

- **Définir une fonction** : permet de regrouper du code réutilisable.
- **Appeler une fonction** : exécute le code de la fonction.
- **Passer des paramètres** : permet de personnaliser le comportement de la fonction.
- **Retourner des valeurs** : permet d’obtenir un résultat après l’exécution.
- **Utiliser des valeurs par défaut** : rend la fonction plus flexible.
- **Arguments variables** : permet de gérer un nombre inconnu d’arguments.
- **Fonctions imbriquées** : utile pour organiser le code dans des cas complexes.
- **Fonctions lambda** : pour des opérations rapides et ponctuelles.
- **Récursivité** : pour résoudre des problèmes qui se décomposent en sous-problèmes similaires.
- **Fonctions comme objets** : permet de manipuler des fonctions comme n’importe quelle variable.
- **Génératrices** : pour produire des séquences de valeurs sans tout stocker en mémoire.
- **Fonctions natives/importées** : pour profiter de la bibliothèque standard ou de modules externes.



## SUJET POUR LA SECTION FONCTION


## **Sujet de projet : Gestionnaire d’élèves**

### **Objectif**

Créer un programme qui permet de gérer une liste d’élèves, d’ajouter des informations, de calculer des statistiques et d’afficher des résultats, en utilisant toutes les notions vues sur les fonctions.

## **Consignes détaillées**

### **1. Variables globales et locales**

- **Variable globale** : une liste qui contient tous les élèves.
- **Variable locale** : chaque fonction manipule des variables locales pour ses calculs.

### **2. Fonctions de base**

- **Ajouter un élève** : fonction qui prend un nom et un âge, et ajoute l’élève à la liste globale.
- **Afficher tous les élèves** : fonction qui affiche la liste des élèves.
- **Rechercher un élève** : fonction qui prend un nom et affiche l’élève correspondant.

### **3. Paramètres et arguments**

- **Fonction avec plusieurs paramètres** : ajouter un élève avec nom et âge.
- **Valeurs par défaut** : option pour ajouter un élève sans âge (par défaut, âge = 18).

### **4. Arguments variables (`*args` et `**kwargs`)**

- **Calculer la moyenne d’âge** : fonction qui prend un nombre variable d’élèves (via `*args` ou `**kwargs`) et retourne la moyenne d’âge.
- **Afficher les informations** : fonction qui prend des arguments nommés (`**kwargs`) pour afficher des détails sur les élèves.

### **5. Fonctions imbriquées**

- **Calculer la note maximale** : fonction principale qui appelle une fonction imbriquée pour trouver la note la plus élevée d’un élève.

### **6. Fonctions lambda**

- **Trier les élèves par âge** : utiliser une fonction lambda pour trier la liste des élèves.

### **7. Fonctions récursives**

- **Compter le nombre d’élèves** : fonction récursive qui compte le nombre d’élèves dans la liste.

### **8. Fonctions génératrices**

- **Générer la liste des âges** : fonction génératrice qui retourne un à un les âges des élèves.

Ce sujet te permettra de :

- **Manipuler des variables globales et locales**
- **Utiliser tous les types de paramètres et d’arguments**
- **Mettre en œuvre des fonctions imbriquées, lambda, récursives, génératrices**
- **Afficher, rechercher, trier et calculer des statistiques**

# correction

## ########################################################################### fin sujet#############################################################################
 


# NOTE ELKAST SUR LA PROGRESSION

J'ESPERE QUE CELA VOUS AIDERA A DEVENIR TRES BON EN PYTHON 