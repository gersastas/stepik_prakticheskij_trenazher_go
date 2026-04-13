У вас есть переменная `message`, которая содержит входные пользовательские данные.

Напишите код, который конвертирует значение строки `message` из **(#1)** в **(#2)** и записывает результат в переменную `result`.

**(#1)** - `.class+.class+.class`

**(#2)** - `<div class="class"></div><div class="class"></div><div class="class"></div>`

**Подсказка!** Для разработки и отладки регулярных выражений используйте: [https://regex101.com](https://regex101.com/)

**Sample Input 1:**

```
.row+.row+.row
```

**Sample Output 1:**

```
<div class="row"></div><div class="row"></div><div class="row"></div>
```

**Sample Input 2:**

```
.col+.col+.col
```

**Sample Output 2:**

```
<div class="col"></div><div class="col"></div><div class="col"></div>
```

**Sample Input 3:**

```
.col-3+.col-3+.col-3+.col-3
```

**Sample Output 3:**

```
<div class="col-3"></div><div class="col-3"></div><div class="col-3"></div><div class="col-3"></div>
```