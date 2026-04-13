У вас есть переменная `message`, которая содержит входные пользовательские данные.

Напишите код, который определяет какому паттерну относится значение строки `message` и записывает результат в переменную `result`. 

Строка может подходить под пять паттернов

1.  kebab-case
2. snake_case
3. lowerCamelCase
4. UpperCamelCase
5. unknown

**Sample Input 1:**

```
the-monster-and-the-superhero
```

**Sample Output 1:**

```
kebab-case
```

**Sample Input 2:**

```
the_monster_and_the_superhero
```

**Sample Output 2:**

```
snake_case
```

**Sample Input 3:**

```
theMonsterAndTheSuperhero
```

**Sample Output 3:**

```
lowerCamelCase
```

**Sample Input 4:**

```
TheMonsterAndTheSuperhero
```

**Sample Output 4:**

```
UpperCamelCase
```

**Sample Input 5:**

```
The Monster And The Superhero
```

**Sample Output 5:**

```
unknown
```