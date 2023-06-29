<h1 align="center">
Coding club - Petit Bain
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

## 1 - my_print_alpha 🔡

Fichier: `my_print_alpha.c`

Ecrivez une fonction qui, en commençant par `a`, affiche l'alphabet dans l'ordre croissant, sur une seule ligne.

**Retour(s) attendus:**

| Valeur |  Type  |
| :----: | :----: |
|   0    | succès |
|   84   | erreur |

Prototype de la fonction:

```c
void my_print_alpha(void);
```

## 2 - my_ispos ➕

Fichier: `my_ispos.c`

Ecrivez une function qui retourne `true` si le chiffre donné en paramètre est positif, ou `false` s'il est négatif ou nul.

**Retour(s) attendus:**

| Valeur |  Type  |
| :----: | :----: |
|   true    | chiffre positif |
|   false   | chiffre négatif ou nul |

Prototype de la fonction:

```c
bool my_ispos(int n);
```

## 3 - my_putnbr 🔢

Fichier: `my_putnbr.c`

Ecrivez une function qui afficher le nombre donné en paramètre (en utilisant seulement `write`).

Prototype de la fonction:

```c
void my_putnbr(int n);
```

Par exemple, `my_putnbr(42)` affiche **42**, `my_putnbr(0)` affiche **0**, `my_putnbr(-2147483647)` affiche **-2147483647**.

## 4 - my_putstr 🖨️

Fichier: `my_putstr.c`

Ecrivez une function qui affiche, un-par-un, les caractères d'une string.
L'adresse du premier caractère de la string sera donné dans le pointer qui est passé en paramètre.

Valeur(s) de retour:

**Retour(s) attendus:**

| Valeur |  Type  |
| :----: | :----: |
|   84    | adresse invalide |
|   84    | string de 0 caractères |
|   0   | succès |

Prototype de la fonction:

```c
int my_putstr(char const *str);
```

## 5 - my_swap 🔄️

Fichier: `my_swap.c`

Ecrivez une function qui échange le contenu de deux chiffres. Leurs adresses sont passés en paramètre.

Prototype de la fonction:

```c
void my_swap(int *a, int *b);
```

## 6 - my_compute_factorial_it 🧮

Fichier: `my_compute_factorial_it.c`

Ecrivez une fonction itérative qui retourne le factoriel du nombre donné en paramètre.

**Retour(s) attendus:**

| Valeur |  Type  |
| :----: | :----: |
|   0    | nb < 0 |
|   >= 1    | !nb |

Prototype de la fonction:

```c
int my_compute_factorial_it(int nb);
```

## 7 - my_getnbr_base 🔟

Fichier: `my_getnbr_base.c`

Ecrivez une function qui convertis et retourne un nombre (donné en tant que string) dans une base donnée en nombre décimal.
The function must deal with negative numbers, and several successive + or - before the number.

| Valeur |  Type  |
| :----: | :----: |
|   -84    | base invalide |
|   0    | string de 0 caractères |
|   >= 1    | nb en base 10 |

Prototype de la fonction:

```c
int my_getnbr_base(char const *str, char const *base);
```

## Finis? 🏁

[Fir_Tree](./Fir_Tree.md)
