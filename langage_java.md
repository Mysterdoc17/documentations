# <center>Le langage Java</center>

## Le Java, c'est quoi ?

- Un langage de programmation *simple* : étant donné que le Java est basé sur le C++ et se rapproche du C#. Java a supprimé de nombreuses fonctionnalités rarement utilisées.

- Un langage indépendant de la plateforme : Java est un langage qui peut être utilisé sur n'importe quelle plateforme. Il utilise un interpréteur JVM (Java Virtual Machine).

- Un langage de programmation orienté objet (POO): il simplifie le programme en plusieurs objets. Ces derniers peuvent être utilisés comme un pont pour que les données circulent d'une fonction à l'autre.

- Un langage *robuste* : les programmes réalisés en Java doivent être fiables car les applications peuvent être utilisées par le grand public (des blu-ray jusqu'aux systèmes de navigation).

- Un langage *multithread* : Java peut effectuer plusieurs tâches à la fois en définissant plusieurs threads. Par exemple, un programme qui gère une interface utilisateur graphique en attendant l’entrée d’une connexion réseau utilise un autre thread à exécuter et à attendre au lieu d’utiliser le thread par défaut de l’interface graphique pour les deux tâches. Cela permet à l'interface graphique de rester sensible.

## Exemple général de code Java :

```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello World!");
    }
}
```

- ```System.out.println("Hello World!");``` : affiche "Hello World!" dans la console.
- ```String[] args``` : les arguments passés à la ligne de commande.
- ```public``` : la visibilité du code.
- ```class HelloWorld``` : le nom de la classe.

## Mots-clés en Java :

- `abstract` : permet de définir une classe abstraite.
- `assert` : permet de définir une assertion.
- `boolean` : permet de définir un booléen.
- `break` : permet de sortir d'une boucle.
- `byte` : permet de définir un byte.
- `case` : permet de définir un cas.
- `catch` : permet de définir une exception.
- `char` : permet de définir un caractère.
- `class` : permet de définir une classe.
- `const` : permet de définir une constante.
- `continue` : permet de continuer dans une boucle.
- `default` : permet de définir un cas par défaut.
- `do` : permet de définir une boucle.
- `double` : permet de définir un double.
- `else` : permet de définir un autre cas.
- `enum` : permet de définir une énumération.
- `extends` : permet de définir une classe fille.
- `final` : permet de définir une constante.
- `finally` : permet de définir un bloc de code à exécuter en fin de programme.
- `float` : permet de définir un float.
- `for` : permet de définir une boucle.
- `goto` : permet de définir un label.
- `if` : permet de définir une condition.
- `implements` : permet de définir une interface.
- `import` : permet de définir une classe à importer.
- `instanceof` : permet de définir une instance.
- `int` : permet de définir un entier.
- `interface` : permet de définir une interface.
- `long` : permet de définir un long.
- `native` : permet de définir une méthode native.
- `new` : permet de définir une nouvelle instance.
- `package` : permet de définir un package.
- `private` : permet de définir une méthode privée.
- `protected` : permet de définir une méthode protégée.
- `public` : permet de définir une méthode publique.
- `return` : permet de retourner une valeur.

## Sources :
- [Documentation de Java](https://docs.oracle.com/javase/8/docs/api/index.html)
- [cours de la plateforme developpement-informatique.com](https://developpement-informatique.com/tutoriel/20/cours-java-pour-les-debutants)