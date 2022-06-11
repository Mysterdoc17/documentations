# <center>Le langage PHP</center>

## Le PHP, c'est quoi ?

- PHP : *Hypertext Preprocessor*
- Open Source : PHP est un langage de programmation libre.
- PHP est un langage de programmation qui est utilisé pour créer des pages web.

## Exemple général de code PHP :

```php
<?php
define('NOM_DE_LA_CONSTANTE', 'valeur');
echo NOM_DE_LA_CONSTANTE;

echo 'Hello World !';
?>
```

- ```echo NOM_DE_LA_CONSTANTE;``` : affiche "valeur".
- ```echo 'Hello World!';``` : affiche "Hello World !".
- ```<?php``` : début du code PHP.
- ```?>``` : fin du code PHP.

## Mots-clés en PHP :

- `echo` : affiche un texte.
- `return` : retourne une valeur (en parlant d'une fonction).
- `if` : conditionnelle.
- `else` : alternative.
- `for` : boucle
- `while` : boucle infinie.
- `foreach` : boucle avec paliers.
- `public` : attribut public.
- `private` : attribut privé.
- `protected` : attribut protégé.
- `static` : attribut statique.
- `abstract` : classe abstraite.

## Les variables en PHP :

- `$nom_de_la_variable` : variable.
- `$_nom_de_la_variable` : variable cachée.
- `$$nom_de_la_variable` : variable globale.
- `$nom_de_la_variable = valeur` : affectation.
- `$nom_de_la_variable = $_POST['nom_du_champ']` : affectation d'un champ du formulaire avec la méthode POST.
- `$nom_de_la_variable = $_GET['nom_du_champ']` : affectation d'un champ du formulaire avec la méthode GET.
- `$nom_de_la_variable = $_SESSION['nom_du_champ']` : affectation d'une variable de session.
- `$nom_de_la_variable = $_COOKIE['nom_du_champ']` : affectation d'une variable de cookie.
- `$nom_de_la_variable = $_FILES['nom_du_champ']` : affectation d'un champ pour un fichier uploadé.
- `$nom_de_la_variable = $_SERVER['nom_du_champ']` : affectation d'un champ du serveur.

## Les classes en PHP :

- `class nom_de_la_classe` : définition d'une classe.
- `public function nom_de_la_fonction() {}` : définition d'une fonction.
- `public function nom_de_la_fonction() { return 'valeur'; }` : définition d'une fonction avec une valeur de retour.
- `public function nom_de_la_fonction() { return $this->nom_de_la_variable; }` : définition d'une fonction avec une variable de classe.
- `public function nom_de_la_fonction() { return $this->nom_de_la_variable = 'valeur'; }` : définition d'une fonction avec une variable de classe et une affectation.

*Résumé :*

```php
// Définition d'une classe
class nom_de_la_classe {

    // définition d'un attribut
    public int $nom_de_la_variable = 0;

    // Définition d'une fonction constructeur
    public function __construct() {
        $this->nom_de_la_variable = 'valeur';
    }
}
```

## Sources :
- [Documentation PHP](https://www.php.net/docs.php)
- [Cours de PHPFacile](http://www.lephpfacile.com/cours/)
- [cours W3School]()