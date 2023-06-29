<h1 align="center">
Coding club - Petit Bain (TIPS)
</h1>

</br>

## Tips 📝

Voici quelques petits coup de pouce pour vous aider à résoudre les exercices:

### Le Coding Style 🎨

Le Coding Style est un ensemble de règles à respecter pour écrire du code propre. Epitech utilise une variante du Coding Style du langage C. Pour tester vos programme avec le Coding Style, vous pouvez utiliser `banana` ou `mango`. Par exemple, `banana . ./reports` vérifie le Coding Style de tous les fichiers dans le dossier courant et affiche les erreurs dans le dossier `./reports`.

### Compiler un programme 🚀

Afin de transformer votre code en exécutable, vous devez le compiler. Pour cela, vous devez utiliser un compilateur. Le compilateur le plus utilisé pour le langage C est `gcc`.

```bash
gcc my_program.c
```

Une fois votre commande exécutée, vous devriez avoir un nouveau fichier dans votre dossier, `a.out`. C'est votre programme compilé. Pour l'exécuter, il vous suffit de taper:

```bash
./a.out
```

Vous pouvez utiliser `gcc -Wall -Wextra -Werror` pour compiler votre programme avec des warnings et erreurs supplémentaires. Par exemple, `gcc -Wall -Wextra -Werror my_program.c` affiche des warnings et erreurs supplémentaires lors de la compilation de votre programme.
Vous pouvez utiliser `gcc -o my_program` pour compiler votre programme avec un nom personnalisé. Par exemple, `gcc -o my_program my_program.c` compile votre programme avec le nom `my_program` au lieu de `a.out`.

### Debug un programme 🐛

Afin de trouver les erreurs dans votre programme, vous pouvez tout simplement utiliser `printf` pour afficher des messages dans votre terminal. Par exemple, `printf("Hello %s, Today's lucky number is %d!\n", "World", 42);` affiche `Hello World, Today's lucky number is 42!` dans votre terminal.

Votre programme peut aussi planter. Vous pouvez utiliser `valgrind` pour trouver les erreurs ainsi qu'utiliser les flags `-g` et `-fsanitize=address` lors de la compilation. Par exemple, `gcc -g -fsanitize=address my_program.c` compile votre programme avec les flags `-g` et `-fsanitize=address`. Une fois votre programme compilé, vous pouvez utiliser `valgrind ./a.out` pour lancer `valgrind` avec votre programme compilé.

Pour avoir `-fsanitize=address` vous devez installer soit `clang` ou la library `libasan`. Pour installer `clang` sur Windows, vous pouvez utiliser `scoop install llvm`. Pour installer `libasan` sur Windows, vous pouvez utiliser `scoop install asan`. Pour installer `libasan` sur Linux, vous pouvez utiliser votre package manager. Par exemple, `sudo apt install libasan5` installe `libasan` sur Debian.

Pour cela, vous pouvez aussi utiliser `gdb` pour trouver l'erreur. Par exemple, `gdb -ex r ./a.out` lance `gdb` avec votre programme compilé. Une fois `gdb` lancé, vous pouvez utiliser `bt` pour afficher la stack trace de votre programme.

### Les manuels 📖

Vous pouvez utiliser `man` pour afficher le manuel d'une fonction. Par exemple, `man write` affiche le manuel de la fonction `write`.

### Les types de données 📚

Vous pouvez utiliser `int` pour définir un nombre entier. Par exemple, `int my_number = 42;` définit une variable `my_number` avec la valeur `42`.
Vous pouvez utiliser `char` pour définir un caractère. Par exemple, `char my_char = 'a';` définit une variable `my_char` avec la valeur `a`.
Vous pouvez utiliser `bool` pour définir un booléen. Par exemple, `bool my_bool = true;` définit une variable `my_bool` avec la valeur `true`.
Vous pouvez utiliser `void` pour définir une fonction qui ne retourne rien. Par exemple, `void my_function(void) { ... }` définit une fonction `my_function` qui ne retourne rien.

### Les opérateurs 🧮

Vous pouvez utiliser `+` pour additionner deux nombres. Par exemple, `int my_number = 1 + 2;` définit une variable `my_number` avec la valeur `3`.
Vous pouvez utiliser `-` pour soustraire deux nombres. Par exemple, `int my_number = 1 - 2;` définit une variable `my_number` avec la valeur `-1`.
Vous pouvez utiliser `*` pour multiplier deux nombres. Par exemple, `int my_number = 1 * 2;` définit une variable `my_number` avec la valeur `2`.
Vous pouvez utiliser `/` pour diviser deux nombres. Par exemple, `int my_number = 1 / 2;` définit une variable `my_number` avec la valeur `0`.
Vous pouvez utiliser `%` pour obtenir le reste de la division de deux nombres. Par exemple, `int my_number = 1 % 2;` définit une variable `my_number` avec la valeur `1`.
Vous pouvez utiliser `==` pour vérifier si deux nombres sont égaux. Par exemple, `bool my_bool = 1 == 2;` définit une variable `my_bool` avec la valeur `false`.
Vous pouvez utiliser `!=` pour vérifier si deux nombres sont différents. Par exemple, `bool my_bool = 1 != 2;` définit une variable `my_bool` avec la valeur `true`.
Vous pouvez utiliser `>` pour vérifier si un nombre est supérieur à un autre. Par exemple, `bool my_bool = 1 > 2;` définit une variable `my_bool` avec la valeur `false`.
Vous pouvez utiliser `<` pour vérifier si un nombre est inférieur à un autre. Par exemple, `bool my_bool = 1 < 2;` définit une variable `my_bool` avec la valeur `true`.
Vous pouvez utiliser `>=` pour vérifier si un nombre est supérieur ou égal à un autre. Par exemple, `bool my_bool = 1 >= 2;` définit une variable `my_bool` avec la valeur `false`.
Vous pouvez utiliser `<=` pour vérifier si un nombre est inférieur ou égal à un autre. Par exemple, `bool my_bool = 1 <= 2;` définit une variable `my_bool` avec la valeur `true`.
Vous pouvez utiliser `&&` pour vérifier si deux booléens sont vrais. Par exemple, `bool my_bool = true && false;` définit une variable `my_bool` avec la valeur `false`.
Vous pouvez utiliser `||` pour vérifier si au moins un booléen est vrai. Par exemple, `bool my_bool = true || false;` définit une variable `my_bool` avec la valeur `true`.
Vous pouvez utiliser `!` pour vérifier si un booléen est faux. Par exemple, `bool my_bool = !true;` définit une variable `my_bool` avec la valeur `false`.

### Les conditions 🚦

Vous pouvez utiliser `if` pour exécuter un bloc de code si une condition est vraie. Par exemple, `if (true) { ... }` exécute le bloc de code si la condition est vraie.
Vous pouvez utiliser `else` pour exécuter un bloc de code si une condition est fausse. Par exemple, `if (false) { ... } else { ... }` exécute le premier bloc de code si la condition est vraie, ou le deuxième bloc de code si la condition est fausse.
Vous pouvez utiliser `else if` pour exécuter un bloc de code si une condition est fausse, et qu'une autre condition est vraie. Par exemple, `if (false) { ... } else if (true) { ... }` exécute le premier bloc de code si la première condition est vraie, ou le deuxième bloc de code si la première condition est fausse et que la deuxième condition est vraie.

### Les boucles 🔄

Vous pouvez utiliser `while` pour exécuter un bloc de code tant qu'une condition est vraie. Par exemple, `while (true) { ... }` exécute le bloc de code tant que la condition est vraie.
Vous pouvez utiliser `for` pour exécuter un bloc de code un certain nombre de fois. Par exemple, `for (int i = 0; i < 10; i++) { ... }` exécute le bloc de code 10 fois.