У вас есть переменная `message`, которая содержит входные пользовательские данные.

Напишите код, который конвертирует значение строки `message` из **(#1)** в **(#2)** и записывает результат в переменную `result`.

**(#1)** - `tagname+tagname+tagname`

**(#2)** - `<tagname></tagname><tagname></tagname><tagname></tagname>`

**Подсказка!** Для разработки и отладки регулярных выражений используйте: [https://regex101.com](https://regex101.com/)

**Sample Input 1:**

```
p+p+p
```

**Sample Output 1:**

```
<p></p><p></p><p></p>
```

**Sample Input 2:**

```
p+p+div
```

**Sample Output 2:**

```
<p></p><p></p><div></div>
```

**Sample Input 3:**

```
div+p+div
```

**Sample Output 3:**

```
<div></div><p></p><div></div>
```