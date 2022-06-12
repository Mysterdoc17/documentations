# <center>Le langage Python</center>

## Le Python, c'est quoi ?

- Facile pour apprendre
- Dynamique
- Peut être utilisé pour :
    + Développement web (côté serveur)
    + développement logiciel
    + Scripts pour le systeme d'exploitation

## Programme "Hello World" :

```python
print("Hello World")
```

- `print` : fonction qui affiche un message

## Les variables et leurs types :

- `var_1 = "Hello"` : déclaration d'une variable
- `var_1` : nom de la variable
- `var_1 = "Hello"` : affectation de la valeur "Hello" à la variable `var_1`
- `print(var_1)` : affichage de la variable `var_1`
- Integer : `int`
- Float : `float`
- String : `str`
- Boolean : `bool`
- List : `list`
- Tuple : `tuple`
- Dictionary : `dict`

## Les fonctions :

- `def` : déclaration d'une fonction
- `fonction_1()` : appel de la fonction `fonction_1`
- `return` : retourne la valeur de la fonction
- `print(fonction_1())` : affichage de la valeur de la fonction `fonction_1`

*Exemple :*

```python
def fonction_1():
    return "Hello"

print(fonction_1())
```

Les fonctions souvent utilisées pour simplifier le code pour éviter de répéter des lignes de code, notamment dans la programmation procédurale.

## Les classes :

*Exemple :*
```python
class Classe_1:
    def __init__(self):
        self.var_1 = "Hello"
```

- `class` : déclaration d'une classe
- `__init__` : constructeur de la classe
- `self` : paramètre du constructeur de la classe
- `self.var_1 = "Hello"` : affectation de la valeur "Hello" à la variable `var_1`

Les classes sont utilisées pour simplifier la programmation en ajoutant les méthodes et les objets, en compléments des fonctions.

## Sources :

- [Documentation officielle Python](https://docs.python.org/3/tutorial/index.html)
- [Cours Python W3Schools](https://www.w3schools.com/python/default.asp)