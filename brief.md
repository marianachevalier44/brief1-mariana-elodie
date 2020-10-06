# BRIEF 1 Decouverte de l'algorithme avec JAVA

## Notions de variables

### Qu'est ce qu'une variable?

Plus précisément, une variable est un conteneur utilisé pour stocker un élément de données dont votre programme pourrait avoir besoin.

Le nom d'une variable doit refléter la signification de son contenu, comme des étiquettes sur une boîte. Voici quelques recommandations générales pour la création de noms :

-   **utilisez des noms descriptifs tout au long de votre code.**  
    Ça risque d'être un peu long ! Cependant, les noms descriptifs sont bien pratiques à long terme pour vous et pour votre équipe, car ils offrent une meilleure lisibilité et facilitent ainsi la compréhension du code pour les autres développeurs. Par exemple, si vous voulez stocker des cookies sans sucres, l'utilisation d'un nom descriptif comme `cookiesSansSucres` est bien plus précis que, disons, `cookies` ou `cookiesSains`.
    
    
-   **Suivez une convention d'appellation commune.**  
    L'une des conventions d'appellation les plus populaires est le  **Camel Case** : une phrase composée de plusieurs mots sans espaces ni ponctuation. Le premier mot est écrit en minuscules et tous les autres mots commencent par une majuscule. Par exemple, `monBudget`.

### Créer une variable avec une déclaration de variable:
Pour utiliser une variable dans votre code, vous devez la créer, ou, en langage de développeur, la _**déclarer**_.
En Java, les  **variables qui contiennent des nombres**  sont déclarées en utilisant un mot clé tel que `int` suivi du nom d'une variable et de sa valeur initiale. Par exemple :
1 int allocationEnCours = 300 ;
2 int epargne = 800 ;
Ici, nous avons déclaré deux variables : `allocationEnCours et `épargne. Ces variables stockent respectivement les valeurs de 300 et 800.

Une variable peut varier, c'est-à-dire **changer de valeur**.
Pour la faire varier, vous pouvez effectuer plusieurs **opérations**.

Il existe huit types de base concernant les variables mais nous en parerons des plus courant notamment :
  - string = texte ;
  - int = entier ;
  - double = nombre en virgule flottante;
En java , on peut déclarer nos 3 variables comme ceci :
**string** text = "une merveilleuse chaine qui consiste à  de multiples caractères ";
**int** nombresDeVoyelles = 0;
**double** purcentageDeVoyelles = 0.0;

**N.B:** Veuillez noter que lorsque vous affectez une valeur à une variable lors de sa déclaration, vous devez indiquer explicitement le type de variable dont il s'agit. Pour ce faire, ajoutez le **type** dans votre **déclaration** en utilisant les mots clés _int_, _String_ ou _double_ dans notre cas ci-dessus.

### Découvrez des variables qui ne changent pas:
Une variable avec une valeur qui ne change pas s'appelle une _**constante**_. Tout comme les autres variables, les constantes sont décrites par trois composantes : **nom, valeur et type**. La seule différence est qu'une fois que vous l'avez définie, la valeur d'une constante ne peut plus être modifiée.

Déclarons quelques constantes et voyons comment elles fonctionnent. Pour déclarer une constante en Java, vous devez utiliser le mot clé final :
 1. final int nombreDeJourDeLaSemaine = 7;
2. final String monRepasFavori = "glace";
3. int nombresAnimaux = 1;
4. String saisonEnCours = "été";

Il y a des variables et des constantes dans l'exemple ci-dessus. Si on essaie de modifier les valeurs de toutes ces variables, seules les variables passeront et les constantes généreront des erreurs :

 nombreDeJourDeLaSemaine= nombreDeJourDeLaSemaine + 1;// Erreur
monRepasFavori = "Cake"; // Error

nombresAnimaux  = 3; // Ok
saisonEnCours  = "Automne"; // Ok
# les types de variables :


**Les variables** se divisent en plusieurs **types**, permettant ainsi de stocker des données différentes selon le besoin.
Lors de la **déclaration** d'une variable, il faut spécifier son type. Toute variable, en plus de son nom, se doit d'avoir un type. 

## Les types primitifs :

#### boolean : 
ne prend en compte que 2 valeurs, **true** et **false**.
#### char (character) : 
permet de stocker la valeur Unicode d'un caractère (entre '\u0000' et '\uffff').

### Les types entier :

#### byte : 
nombre entier relatif très court (entre -128 et 127).
#### short : 
nombre entier relatif court (entre -32 768 et 32 767).
#### int (integrer) : 
nombre entier relatif (entre -2 147 483 648 et 2 147 483 647).
#### long : 
nombre entier relatif court (entre -32 768 et 32 767).

### Les types flottants :
**float** et **double** se distinguent par la taille de leur représentation, et par conséquent par la précision et l'étendue des valeurs.

#### float : 
nombre décimal, permettant la virgule (entre − 3 , 4.10^38 et 3 , 4.10^38).
#### double : 
nombre décimal, permettant la virgule (entre − 1 , 7.10^308 et 1 , 7.10^308).


## Affectation :

Une **affectation** équivaut à mettre une valeur dans une variable.
Comment affecter la valeur d'une variable?

* taper une valeur littéral après le signe égal : x = 12; test = true;
* affecter la valeur d'une variable à une autre : y = x;
* employer une expression combinant les deux : x = y + 3;

#### Exemples : 
```java
int taille = 32;
char initiale = 'j'; // ne pas oublier les ' '
double d = 431.123; // le point joue le rôle de la virgule.
boolean test; 
test = true; // les booléens et les entiers sont différents.
float = 32.4f; // le f différencie les floats des doubles.
```
# Les mots-clés
Les mots-clés sont des termes spécifiques au langage de programmation, certains sont utilisables par plusieurs langages et d'autres spécifiques à un langage.
On trouve plus de 50 mots clés qui ont les usages propres en java.
On ne peut les utiliser que dans un contexte précis et il est impossible de les déclarer en comme noms de classes ou variables. 
On retrouve différents types de mots-clés; des mots-clés pour déclarer des objets, variables, des états, des branchements et encore des exceptions.

Les mots pour les objets; "class", "interface", "implements", "enum", "import", "this", "abstract", "extends", "package", "super" &"native".

Les mots pour les types; "boolean", "char", "int", "float", "long", "short", "double", "byte" & "void".

Pour les états; "const" , "false", "true", "static", "null", "volatile", "new", "transient", "strictfp".

pour les boucles: "do", "for", "goto", "while", "continue".

pours les branchements; "if", "else", "return", "break", "assert", "switch", "synchronized", "default", "case" & "instanceof".

Et voici les mots-clés pour gérer des exceptions; "throw", "throws", "try", "catch" & "finally"
# Les opérateurs
## Qu'est ce qu'un opérateur?

Les opérateurs sont des symboles qui permettent de manipuler des variables, c'est-à-dire effectuer des opérations, les évaluer. 

On distingue plusieurs types d'opérateurs:

-   les opérateurs de calcul
-   les opérateurs d'assignation
-   les opérateurs d'incrémentation
-   les opérateurs de comparaison
-   les opérateurs logiques
-   (les opérateurs bit-à-bit)
-   (les opérateurs de rotation de bit)

**Les opérateurs de calcul** permettent de modifier mathématiquement la valeur d'une variable.


|-|  Soustraction: Soustrait deux valeurs
|+| Addition: Ajoute deux valeurs
|*| Multiplication: Multiplie deux valeurs
|/| Division: Calcul le quotient de la division de deux valeurs
|%| Congruence: Calcul le reste de la division de deux valeurs
|=| D'affectation: Affecte une valeur à une variable.

**Les opérateurs d'assignation** permettent de simplifier des opérations telles que _ajouter une valeur dans une variable et stocker le résultat dans la variable_.

Avec les opérateurs d'assignation il est possible d'écrire cette opération sous la forme suivante :_x+=2_  
Ainsi, si la valeur de x était 7 avant opération, elle sera de 9 après...
Les autres opérateurs du même type sont les suivants :

|+=|
|-=|
|*=|
|/=|
|%=|

**Les opérateurs d'incrémentation**: permettent de facilement augmenter ou diminuer d'une unité une variable. Ces opérateurs sont très utiles pour des structures telles que des boucles, qui ont besoin d'un compteur (variable qui augmente de un en un).
Un opérateur de type _x++_ permet de remplacer des notations lourdes telles que _x=x+1_ ou bien _x+=1_

Exemple:  Int X = 7
++ incrémentation ; synthaxe X++ ou ++X Résultat: 8
-- décrémentation ; synthaxe X-- ou --X Résultat: 6
**Remarque :**  la différence entre x++ ou ++x se fait ressentir lorsque l'on combine plusieurs opérations.  
Avec x++ on utilise la valeur de x puis on ajoute 1, alors qu'avec ++x on ajoute d'abord 1, puis on utilise le résultat. Il en va de même pour x-- et --x.  
  
Exemples (pour x=7)

-   int y=x++; 
    y est initialisé à 7, puis x est incrémenté à 8
-   int y=++x;
     x est incrémenté à 8, puis y est initialisé à 8

**Les opérateurs de comparaison**
|== |opérateur d'égalité à ne pas confondre avec |=| affectation; compare 2 valeurs et vérifie leur égalité. Exple: X==3 : retourne true si x est égale à 3 sinon faux.

|<| d'infériorité stricte ; Exple: d'infériorité stricte ; Retourne _true_ si x est inférieur à 3, sinon _false_

|<=| d'infériorité; Exple: Retourne _true_ si x est inférieur ou égal à 3, sinon _false_

|>| supériorité stricte; Exple : Retourne _true_ si x est supérieur à 3, sinon _false_

|>=| supériorité; Exple : Retourne _true_ si x est supérieur ou égal à 3, sinon _false_

|!=| différence; Exple : Retourne _true_ si x est différent de 3, sinon _false_.

**Les opérateurs logiques** permettent de vérifier si plusieurs conditions sont vraies :
**||**: Ou logique; Retourne _true_ si au moins une des deux conditions vaut _true_ (ou _false_ sinon) [Synthaxe : condition 1 || condition 2]

**&&**: Et logique; Retourne _true_ si les deux conditions valent _true_ (ou _false_ sinon) [synthaxe : condition 1 && condition 2]

**!**: NON logique; Retourne _true_ si la variable vaut _false_, et _false_ si elle vaut _true_) [synthaxe: !condition].

**Remarque :** il n'est pas toujours nécessaire de faire tous les tests pour connaître le résultat d'un calcul.  
Par exemple le résultat de _(true || x)_, vaudra toujours _true_ quelque soit la valeur x.  
Il est donc intéressant de savoir que Java évalue les valeurs de gauche à droite pour économiser les calculs.
# L'évaluation 

Lorsque une opération doit avoir lieux, la priorité opératoire s'applique. Par exemple, comme vu précédemment, les variables de type *double* contiennent plus d'informations de type *int*.

Lors d'une opération, Java va donc retourner un résultat de l'opération qui sera **"caster"** selon les type de variable.

> int nbre1 = 3  
int nbre2= 2  
double resultat = nbre1 / nbre2  
// le résultat sera 1  

Le résultat de cet exemple sera un entier. En effet la priorité opératoire est en faveur du type int. Si l'on veut obtenir 1,5, il nous faudra faire un *cast* sur le résultat, en apposant le type désiré entre parenthèse devant chaque membre de l'opération.

> int nbre1 = 3  
int nbre2= 2  
double resultat = double(nbre1) / double(nbre2)  
// le résultat sera 1.5

Ainsi en Java, chaque membre d'une opération passe automatiquement et implicitement par une évaluation de son type et par un cast si besoin.

Lorsque l’opérande de gauche n’est pas un tableau, il s'éxecute dans cet ordre:

1. Vérifier que l’opérande est une variable déclarée
2. Sauvegarder la valeur de l’opérande gauche

3. Évaluer l’opérande de droite

4. Effectuer l’opération binaire indiquée par l’opérateur composé

5. Convertir le résultat de l’opération binaire en type de variable de gauche **(casting implicite)** . Affecter le résultat converti à la variable de gauche
# L'assignation

En programmation informatique, une affectation, ou assignation, est une structure qui permet d'attribuer une valeur à une variable.


En JAVA, **il faut déclarer toute les variables en précisant leur type** . On peut éventuellement ajouter des modificateurs. Ainsi déclarer une variable « final » revient à créer une constante car le compilateur refusera toutes les instructions modifiant la valeur de cette variable.  
On peut effectuer une affectation ou assignation (donner une valeur) en déclarant une variable.  
**Lors de sa création une variable reçoit toujours une valeur par défaut** . (0 pour les entiers, 0.0 pour les flottants, false pour les booléens, null pour les objets).

**Le signe égal ( = ) est le symbole basique d'assignation.**


```
// déclaration de a comme entier
int a ;
//affectation de a avec la valeur 3
a = 3;
```

Cette instruction déclare une nouvelle variable x , attribue à x la valeur de 3 et renvoie 3 .

Il existe d'autre opérateur d'assignation :

    = Affecte une valeur à une variable
    += Addition
    -= Soustraction
    *= Multiplication
    /= Division
    %= Modulo
    &= ET logique et binaire
    |= OU logique et binaire

*Exemple* : Si l’on a x=4 et que l’on fait x+=3, alors x vaudra 7.   

Ceci est la même chose avec tous ces opérateurs d'assignation.
# L'instruction

C'est quoi?
<p><br>Une instruction informatique désigne une étape dans un programme informatique.</br>
<p>Une instruction dicte à l'ordinateur l'action nécessaire qu'il doit effectuer avant de passer à l'instruction suivante. </p>
<p>Un programme informatique est constitué d'une suite d'instructions.</p>

En java, une instruction se termine par un point virgule `;`

```exemples

System.out.println("Hello World"); // ceci est une instruction

int resultat = 1 + 1; // ceci est une autre instruction

String resultat2 = "Je suis un texte" // une troisième instruction

```

Les instructions se lisent de haut en bas.

```en java

int nombre1 = 1; // première instruction

int nombre2 = 1 + 1; //deuxième instruction

int nombre3 = nombre2 + nombre1; // troisième instruction

```

Dans le code précédent, les instructions sont soit indépendantes, soit dépendantes.

`nombre1` et `nombre2` se voient assignés une valeur par assignation directe ou via une opération mathématique `(1 + 1)`

`nombre3` se voit assigné une valeur via l'addition de `nombre1` et `nombre2`.

Il ne serait pas possible d'assigner de à `nombre3` si `nombre1` et `nombre2` avaient été déclarés après.

```en java

int nombre3 = nombre2 + nombre1; // Erreur, nombre1 et nombre2 n'existent pas encore

int nombre1 = 1; 

int nombre2 = 1 + 1; 

```
# Le bloc d'instructions

Avant de définir ce qu'est un bloc d'instruction, il faut définir ce qu'est une instruction.

Une instruction informatique désigne une étape dans un programme informatique. 

Une instruction dicte à l'ordinateur l'action nécessaire qu'il doit effectuer avant de passer à l'instruction suivante. 

En java, une instruction se termine par un point virgule `;`

```java

System.out.println("Hello World"); // ceci est une instruction

int resultat = 1 + 1; // ceci est une autre instruction

String resultat2 = "Je suis un texte" // une troisième instruction

```

Les instructions se lisent de haut en bas.

```java

int nombre1 = 1; // première instruction

int nombre2 = 1 + 1; //deuxième instruction

int nombre3 = nombre2 + nombre1; // troisième instruction

```

Dans le code précédent, les instructions sont soit indépendantes, soit dépendantes.

`nombre1` et `nombre2` se voient assignés une valeur par assignation directe ou via une opération mathématique `(1 + 1)`

`nombre3` se voit assigné une valeur via l'addition de `nombre1` et `nombre2`.

Il ne serait pas possible d'assigner `nombre1` et `nombre2` à `nombre3` si `nombre1` et `nombre2` avaient été déclarés après.

```java
int nombre3 = nombre2 + nombre1; // Erreur, nombre1 et nombre2 n'existent pas encore

int nombre1 = 1; 

int nombre2 = 1 + 1; 

```

Un programme informatique est constitué d'une suite d'instructions qui s'exécutent dans un `bloc d'instructions`.

### Déclaration d'un bloc d'instructions

En java, un bloc d'instructions se déclare entre crochets `{}`

Les conditions `if/else/else if` sont des blocs d'instructions.

```java

if(true){
    /*
    instruction 1;
    instruction2;
    ...
    */
}else{
    /*
    instruction 1;
    instruction2;
    ...
    */
}else{
    /*
    instruction 1;
    instruction2;
    ...
    */
}
```

Les boucles `for/while/do while` sont des blocs d'instructions.

```java
    for(int i=0;i<100;i++){
        /*
    instruction 1;
    instruction2;
    ...
    */
    }

    while(true){
        /*
    instruction 1;
    instruction2;
    ...
    */
    }

    do{
/*
    instruction 1;
    instruction2;
    ...
    */
    }while(true);
```

Les méthodes de classe sont des blocs d'instruction.

```java
public void function bonjour(){
    /*
    instruction 1;
    instruction2;
    ...
    */
}
```
Les classes sont des blocs d'instruction.

```java

public class MaClasse{
    
    public void method1(){}

    public void method2(){}

    //...
}
```

Chaque bloc d'instruction définit la durée de vie des instructions qui sont déclarées à l'intérieur.

Ainsi dans une fonction, les instructions à l'intérieur ne sont pas accessibles à l'extérieur. Les variables déclarées à l'intérieur n'existent plus une fois le bloc d'instruction terminé

```java

public function MaMethode(int nombre, int nombre2){
    int addition =  nombre1 + nombre2;

    return addition;
}

int resultat = MaMethode(10,10);

System.out.println(addition) // Erreur, addition n'existe pas en dehors de la méthode MaMethode

```

Si une variable est déclarée dans un bloc d'instruction, elle n'existe plus en dehors de ce bloc.

```java

if(true){
    int nombre = 10;
}else{
    nombre = 20; //Erreur, nombre n'existe que dans if, pas dans else
}
```

Par contre

```java

public void function maMethode(){
    int nombre = 0;

    if(true){
        nombre = 10; //ok
    }else{
        nombre = 20; //ok
    }
}


```

`nombre` est défini en amont des blocs d'instruction if et else dans la méthode `maMethode`, les blocs d'instruction enfants peuvent donc récupérer la variable `nombre`.

Un bloc d'instruction enfant peut lire les variables de son parent mais pas l'inverse, la fin d'une instruction signifiant la fin de vie de toutes les instructions à l'intérieur. 

Comme le bloc d'instruction parent n'est pas fini, ses variables sont encore accessibles.

# Les commentaires
Les commentaires permettent de rendre votre code lisible et surtout d'en faciliter ultérieurement la maintenance.

En général, l'insertion de commentaire se fait soit en fin de ligne, soit sur une nouvelle ligne mais en aucun cas au sein d'une ligne de commande.

> ♦Ils ne sont pas pris en compte par le compilateur donc ils ne sont pas inclus dans le pseudo code
♦ils ne terminent pas par un ;
♦Il existe trois types de commentaires en Java.
♦Types de commentaires en Java :

**1-Commentaire sur une seule ligne**
La première consiste à placer un double slash (//) 
♦Syntaxe:
`public class Main {
  public static void main(String[] args) {
    //Afficher le message Hello World!
    System.out.println("Hello World!");
  }
}`
♦Sortie: Hello World!

**2-Commentaire sur plusieurs lignes**
La seconde solution est d'encadrer le texte par un slash suivi d'une étoile (/*) et la même séquence inversée (*/)
♦Syntaxe:
`/*
  Ceci est un commentaire 
  sur plusieurs 
  lignes
*/`

♦Example:
`public class Main {
  public static void main(String[] args) {
    /*
        Déclarer et afficher
        le message Hello World!
    */
    String str = "Hello World!";
    System.out.println(str);
  }
}`
♦Sortie: Hello World!

**3-Commentaire de documentation**
Ce type de commentaires est généralement utilisé lors de l’écriture du code pour un projet, car il permet de générer une page de documentation de référence, qui peut être utilisée pour obtenir des informations sur les méthodes, ses paramètres, etc.
♦Syntaxe:
`**
*
*-Ceci est un Commentaire 
*- de documentation
*
**/`
♦Example:
` /**
 *
 *Programme Java pour déclarer et afficher
 *le message Hello World!
 *-
 *- @author  Thomas babtise
 *-@version 2.5 
 *-@since   2021-12-10
 *-@link    www.waytolearnx.com
 *-
 **/
public class Main {
  public static void main(String[] args) {
    String str = "Hello World!";
    System.out.println(str);
  }
}`

♦Sortie: Hello World!

# La condition


Une condition va vous permettre d'exécuter une portion de code ou non en fonction du résultat de variables booléennes, c'est à dire que vous pourrez dire "si X est faux alors je fais ça, sinon ceci et si aucune des conditions précédentes n'est remplie, je ferais plutôt cela".

# Exemple d'une condition

```java
public boolean variable = true;

if(variable == true)
{
     //Si variable = a vrai(true) alors on execute ce code
     System.out.println("La variable est vrai");
}
```

### Les opérateurs de comparaison

Permet de comparer des valeurs ou de savoir si la condition est vrai ou fausse 

```java
public int var = 5;
```

| Opérateur | Dénomination | Effet | Exemple | Résultat |
| ------ | ------ | ------ | ------ | ------ |
| == | opérateur d'égalité | Compare deux valeurs et vérifie leur égalité | var == 5 | Retourne vrai si var égale 5
| < | opérateur d'infériorité stricte | Verifie qu'une variable est strictement inférieure | var < 4 | Retourne faux car 5 et pas plus petit que 4
| <= | Opérateur d'inféririoté | Vérifie qu'une variable inférieure ou egale | var <= 5 | Retourne vrai car 5 et egale a 5
| >= | Opérateur de superiorité | Vérifie qu'une variable est supérieure ou égale à une valeur | var >= 2 | Retourne vrai car 5 et superieur a 2
| != | Operateur de différence | Vérifie qu'une variable est supérieure ou égale à une valeur | var != 5 | Retourne faux car 5 n'est pas different de 5

### Autres exemples 

```java
public int variable = 5;

if(variable == 5)
{
     //Si variable == 5 on execute ce code
     System.out.println("La variable est a 5 donc le code s'execute");
}
```

```java
public int variable = 10;

if(variable <= 5)
{
     //Si variable est inférieure ou egale 5 on execute ce code
     System.out.println("Ce code ne s'execute pas");
}
```

# Sinon (else)
Il existe une autre facon d'écrire des conditions que seulement avec des si (if) on peut ecrire une condition avec un sinon(else) à la suite d'un if(si), else signifie que si une condition et pas vrai alors on execute un autre bout de code 


### Exemple avec Else

```java
public int variable = 10;

if(variable <= 5)
{
     //Si variable est inférieure ou egale 5 on execute ce code
     System.out.println("Ce code ne s'execute pas");
} else
{
    //Sinon on execute ce code
    System.out.println("Ce code s'execute");
}
```

On peut aussi combiné un else avec un if
### Exemple avec Else If
```java
public int variable = 10;

if(variable <= 5)
{
     //Si variable est inférieure ou egale 5 on execute ce code
     System.out.println("Ce code ne s'execute pas");
} else if (variable == 10)
{
    //Sinon si variable == 10 on execute ce code
    System.out.println("Ce code s'execute");
}
```

# La Boucle

Les boucles permettent de **répéter une ou plusieurs instructions**, selon les conditions désirées.

On en compte plusieurs types:
<br>

## La boucle FOR

Elle permet de contrôler exactement le nombre de répétitions (d'*itérations*) de la boucle.
C'est la plus compliquée à appréhender de toutes parce qu'elle demande plusieurs paramètres.
Sa structure est composée de telle manière:

```java
for( <initialisation> ; <condition> ;  <incrémentation>) {
    <actions>
}
```

Souvent, on utilise une variable temporaire qui garde le compte du nombre d'itérations. Elle est souvent appelée `i` comme *index*, et est un point de repère pour la boucle et le développeur ; mais elle peut s'appeler n'importe comment.

- Dans l'**initialisation** de la boucle, on définit quel est l'état de la boucle avant sa première répétition ; par exemple
`int i = 0`.
Dans cet exemple, on définit une variable i étant égale à 0.

- Dans la **condition** de la boucle, on définit quel est la condition d'arrêt de la boucle ; par exemple
`i <= 20`.
Dans cet exemple, la boucle se répétera tant que la valeur de notre *i* sera inférieure ou égale à 20.

- Dans le paramètre d'**incrémentation** de la boucle, on définit ce qui change à chaque répétition, et qui va permettre à la boucle de se finir à un moment donné. Par exemple:
`i++`.
Dans cet exemple, à chaque répétition de la boucle, la valeur de `i` s'augmente de 1.

## Résultat

Voilà ce que donne nos exemples appliqués ensemble:

```java
for( int i=0 ; i <= 20 ; i++){
    System.out.println(i);
}
```

Cet exemple dans la console nous renverra à chaque répétition la valeur de `i`, jusqu'à 20.

## FOR avec une array

On peut utiliser For pour faire une action pour chaque variable d'une array, par exemple :

```java
for (int i=0; i<myArray.length; i++) {
    System.out.println(myArray[i]);
}
```

Cet exemple enverra chaque objet de l'array dans la console tour à tour.
<br>

## La boucle WHILE

La boucle while permet de créer une boucle avec pour seule instruction sa condition de répétition (s'imaginer while comme "*tant que* \<condition>, faire \<actions>".
Elle s'écrit comme dans cet exemple:

```java
while(i<20){
    i++;
}
```

<br>

## La boucle DO... WHILE

Cette boucle ressemble beaucoup à la précédente, à l'exception que sa condition est écrite après son action, garantissant que la boucle s'éxécute au moins une fois.
Exemple:

```java
int i = 0;

do{
    System.out.println("coucou");
} while(i ==1);
```

Affichera une fois *"coucou"*, même si la condition n'est jamais respectée.

<br>

## Pour aller plus loin

### L'instruction *continue*

Dans une boucle, on peut utiliser `continue` pour dire qu'une partie du code ne doit pas s’exécuter selon certaines conditions:

```java
while(i<20){
    i++;
        if(i ==5){
            continue;
        }
    System.out.println("coucou");
    }
```

La suite du code ne s'exécute pas lorsque `i` est égal à 5, et donc n'affichera pas *"coucou"* à ce moment là.

## L'instruction *break*

On peut utiliser `break` pour arrêter une boucle à un moment voulu, même si la condition de la boucle n'est pas encore respectée:

```java
while(i<20){
    i++;
    if(i ==5){
        break;
    }
}
````

Au moment où `i` sera égal à 5, la boucle s'arrêtera complêtement, alors même que `i` n'est pas encore supérieur ou égal à 20.

# La fonction (appelée méthode de classe en Java)

La fonction ou méthode de classe est un bloc d'instruction réutilisable permettant de recevoir des arguments.

Plutôt que de répéter plusieurs opérations identiques, il suffit de créer une fonction et de mettre ces opérations à l'intérieur.

Aisin si l'on voulait effectuer une opération mathématiques sur deux valeurs on pourrait le faire de cette façon:

```java

int addition = 2+2;

int soustration = 5 - 3;

float division = 10 / 2;

int multiplication = 4 * 7;

```

Grâce aux fonctions, il est possible d'encapsuler ces opérations:

```java

public int function Addition(int nombre1, int nombre2){
    return nombre1 + nombre2;
}

public int function Soustraction(int nombre1, int nombre2){
    return nombre1 - nombre2;
}

public float function Division(float nombre1, float nombre2){
    return nombre1 / nombre2;
}

public int function Multiplication(int nombre1, int nombre2){
    return nombre1 * nombre2;
}

```

### Déclaration d'une méthode de classe

La déclarion d'une méthode de classe/fonction s'éffectue d'abord par la déclaration de sa portée.

- `public` : accès publique. La méthode est disponible depuis partout, par toutes les classes.
- `protected` : accès protégé. La méthode n'est disponible qu'à l'intérieur d'une classe. Elle peut être donc visible pour les classes héritantes. Elle est aussi visible pour des classes non héritantes mais étant du même package.
- `private` : accès privé. La méthode n'est disponible qu'à l'intérieur d'une classe. Héritée, elle n'est pas visible.
 
Puisqu'en java, tout est objet, une méthode appartient obligatoirement à une classe.

une méthode de classe peut être déclarée `static`. Quand une méthode est déclarée `static`, elle ne peut être appelée que par la classe elle-même et non par une instance de classe. 

```java

class MaClass{
    public static void MaMethodeStatique(){
        System.out.print.ln('Je suis appelée par une classe");
    }

    public void MaMethode(){
        System.out.print.ln('Je suis appelée par une instance de classe");
    }
}

```
`MaMethodeStatique` ne peut être appelée que par `MaClass` quand `MaMethode` ne pourra être appelée que par une instance de `MaClass`

Il faut ensuite définir le type de retour de la fonction.
Une fonction peut ou non retourner un résultat.

Sans retour de résultat, il faudra déclarer la méthode par le mot clé `void`.

Selon la valeur de retour, il faudra déclarer le retour comme étant un `int`,`float`,`char`,`String`...

La fonction se déclare avec le mot clé `function` puis par le nom qu'on veut lui donner. Ce sera ensuite son identifiant pour l'appeller (`Addition`, `Soustraction`...).

Les arguments qu'on veut injecter dans cette fonction se déclarent entre parenthèses `()`.

Le traitement des arguments et autres opérations propres à la fonction se déclarent entre crochets  `{ }`. 

Si la méthode renvoit un résultat, le bloc d'instruction se terminera par l'instruction `return` puis le résultat à retourner.

Une fois la fonction déclarée, il est ensuite possible de l'utiliser à l'infini en l'appelant dans notre code:



```java

int resultatAddition = Addition(5,10);
int resultatAddition2 = Addition(6,9);

int resultatSoustraction = Soustraction(100,50);
int resultatSoustraction2 = Soustraction(4,1);

float resultatDivision = Division(10.0,4.0);
float resultatDivision2 = Division(300.0,8.0);

int resultatMultiplication = Multiplication(2,2);
int resultatMultiplication2 = Multiplication(5,9);

```
# Les Paramètres
Les paramètres sont utilisées **par les fonctions** pour leur **donner du matériel avec lequel travailler**.

## Théorie

Lors de la déclaration d'une fonction, on lui indique à l'avance les outils dont elle aura besoin, entre parenthèses, juste après le nom de la fonction.
On sépare plusieurs paramètres par des virgules.
Exemple:

```java

fonction maFonction(int monParametre){
    <actions>
}

```

## Utilisation

Lors de **l'appel** d'une fonction, on donne entre parenthèses les valeurs que la fonction utilisera comme paramètres.
Exemple:


```java

fonction monProfil(String monAge, String monPrenom){
    return monPrenom + " a " + monAge + "ans."
}

String prenom = "Jean-Bob";

monProfil("12", prenom);

```

Notre fonction renverra ainsi *"Jean-Bob a 12 ans"*

## Cas d'exemple: pour conditionner

On peut aussi utiliser des paramètres pour donner des **conditions** pour l’exécution du code au sein d'une fonction
Exemple: 

```java

bool buMonCafé = true;
bool prisMonPC = true;

bool jeSuisPrêt = (buMonCafé && prisMonPC);

fonction commencerJournee(bool ready){
    if(ready){
        aller_a_simplon();
    }
}

commencerJournee(jeSuisPrêt);

```
