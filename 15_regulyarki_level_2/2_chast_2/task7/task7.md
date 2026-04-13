У вас есть переменная `message`, которая содержит входные пользовательские данные.

Напишите код, который конвертирует значение строки `message` из **(#1)** в **(#2)** и записывает результат в переменную `result`.

**(#1)** - `tagname*N`

**(#2)** - `<tagname></tagname><tagname></tagname><tagname></tagname> ...`

`N` - это число повторений тега

**Подсказка!** Для разработки и отладки регулярных выражений используйте: [https://regex101.com](https://regex101.com/)

**Sample Input 1:**

```
p*3
```

**Sample Output 1:**

```
<p></p><p></p><p></p>
```

**Sample Input 2:**

```
div*3
```

**Sample Output 2:**

```
<div></div><div></div><div></div>
```

**Sample Input 3:**

```
div*6
```

**Sample Output 3:**

```
<div></div><div></div><div></div><div></div><div></div><div></div>
```