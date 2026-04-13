У вас есть переменная `message`, которая содержит входные пользовательские данные.

Напишите код, который конвертирует значение строки `message` из **(#1)** в **(#2)** и записывает результат в переменную `result`.

**(#1)** - `tagname>tagname>tagname`

**(#2)** - `<tagname><tagname><tagname></tagname></tagname></tagname>`

**Sample Input 1:**

```
p>p>p
```

**Sample Output 1:**

```
<p><p><p></p></p></p>
```

**Sample Input 2:**

```
p>p>div
```

**Sample Output 2:**

```
<p><p><div></div></p></p>
```

**Sample Input 3:**

```
div>p>div
```

**Sample Output 3:**

```
<div><p><div></div></p></div>
```