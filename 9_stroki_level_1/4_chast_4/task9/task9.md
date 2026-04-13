У вас есть переменная `message`, которая содержит входные пользовательские данные.

Напишите код, который удаляет в строке `message` все лишнее пробелы и записывает результат в переменную `result`. 

**Лишние проблемы это:**

- пробелы в начале и в конце строки 
- пробелы которые идут более одного подряд

**Важно!**

- Учитывайте то что ваш код должен работать как с кириллицей так и с латиницей.

**Sample Input 1:**

```
 Всегда  есть два, не  больше,   не меньше.   Мастер  и  ученик  —  Йода.
```

**Sample Output 1:**

```
Всегда есть два, не больше, не меньше. Мастер и ученик — Йода.
```

**Sample Input 2:**

```
  Fear  is    the  path  to the dark side. Fear   leads to anger. Anger leads to   hate. Hate leads   to suffering - Yoda.
```

**Sample Output 2:**

```
Fear is the path to the dark side. Fear leads to anger. Anger leads to hate. Hate leads to suffering - Yoda.
```