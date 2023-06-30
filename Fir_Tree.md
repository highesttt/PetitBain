<h1 align="center">
Coding club - Petit Bain (PART 2)
</h1>

</br>

## Prérequis 🔑

Pour pouvoir suivre cette activitée, vous devez avoir installé sur votre ordinateur:

- Un éditeur de texte (Visual Studio Code, Atom, Sublime Text, ...)
- Un terminal (Powershell, Terminal, ...)
- Un compilateur C (gcc, clang, ...)

## Les Règles 🧾

- Toute IA est interdite; ChatGPT, Google Bard, Bing AI, Github Copilot, etc.
- Toute forme de plagiat est interdite; vous devez écrire votre code vous-même.
- Vous pouvez utiliser internet pour chercher de l'aide, mais vous ne pouvez pas copier/coller du code.
- Vous devez seulement utiliser `write` pour les exercices.
- Jouez le jeu, les conditions en piscine seront pire 😉

# Exercices 📝

## Fir Tree 🎄

Ecrivez une function qui affiche un sapin de taille `size` donnée en paramètre.

- Si `size` est négatif ou nul, la fonction doit afficher une ligne vide.

Prototype de la fonction:

```cpp
void tree (int size ) ;
````

Fichiers: `main.c`, `my_putchar.c`, `tree.c`

```text
Vous pouvez trouver un binaire appelé, tree dans le repo avec la description du projet.
```

N'oubliez pas que vous devez avoir une politique de test cohérente pour vous assurer que les sorties de votre programme sont correctes. Pour ce faire:

- séparez vos fonctions en autant de petites fonctions que possible, de sorte que chaque fonction soit responsable d'une seule chose (selon le style de codage),
- Testez chacune de vos fonctions individuellement ET essayez d'automatiser votre processus de test avec des scripts (shell?).

## Exemples

```text
~/fire_tree> ./a.out 1
   *
  ***
 *****
*******
   |
```

```text
~/fire_tree> ./a.out 5
                   *
                  ***
                 *****
                *******
                 *****
                *******
               *********
              ***********
             *************
              ***********
             *************
            ***************
           *****************
          *******************
         *********************
           *****************
          *******************
         *********************
        ***********************
       *************************
      ***************************
     *****************************
       *************************
      ***************************
     *****************************
    *******************************
   *********************************
  ***********************************
 *************************************
***************************************
                 |||||
                 |||||
                 |||||
                 |||||
                 |||||
```
