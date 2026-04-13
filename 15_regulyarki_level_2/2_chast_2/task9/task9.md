У вас есть переменная `message`, которая содержит входные пользовательские данные.

Напишите код, который конвертирует значение строки `message` из **(#1)** в **(#2)** и записывает результат в переменную `result`.

**(#1)** - `.class>.class>.class`

**(#2)** - `<div class="class"><div class="class"><div class="class"></div></div></div>`

**Подсказка!** Для разработки и отладки регулярных выражений используйте: [https://regex101.com](https://regex101.com/)

**Sample Input 1:**

```
.wrapper>.block>.block-body
```

**Sample Output 1:**

```
<div class="wrapper"><div class="block"><div class="block-body"></div></div></div>
```

**Sample Input 2:**

```
.wrap>.block>.block-body
```

**Sample Output 2:**

```
<div class="wrap"><div class="block"><div class="block-body"></div></div></div>
```

**Sample Input 3:**

```
.wrap>.block>.body
```

**Sample Output 3:**

```
<div class="wrap"><div class="block"><div class="body"></div></div></div>
```