У вас есть переменная `message`, которая содержит входные пользовательские данные.

Напишите код, который конвертирует значение строки `message` из **(#1)** в **(#2)** и записывает результат в переменную `result`.

**(#1)** - `link[rel=VALUE1 title="VALUE2"]`

**(#2)** - `<link rel="VALUE1" href="" title="VALUE2">`

**Подсказка!** Для разработки и отладки регулярных выражений используйте: [https://regex101.com](https://regex101.com/)

**Sample Input 1:**

```
link[rel=prefetch title="Hello world"]
```

**Sample Output 1:**

```
<link rel="prefetch" href="" title="Hello world">
```

**Sample Input 2:**

```
link[rel=prefetch title="Hello Lia"]
```

**Sample Output 2:**

```
<link rel="prefetch" href="" title="Hello Lia">
```

**Sample Input 3:**

```
link[rel=prefetch title="Lia"]
```

**Sample Output 3:**

```
<link rel="prefetch" href="" title="Lia">
```