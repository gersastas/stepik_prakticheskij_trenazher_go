У вас есть переменная `message`, которая содержит входные пользовательские данные.

Напишите код, который конвертирует значение строки `message` из **(#1)** в **(#2)** и записывает результат в переменную `result`.

**(#1)** - `tagname.class1.class2.classN`

**(#2)** - `<tagname class="class1 class2 classN"></tagname>`

**Sample Input 1:**

```
p.p.lead
```

**Sample Output 1:**

```
<p class="p lead"></p>
```

**Sample Input 2:**

```
a.btn.btn-primary
```

**Sample Output 2:**

```
<a class="btn btn-primary"></a>
```