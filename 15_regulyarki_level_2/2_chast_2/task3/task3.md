У вас есть переменная `message`, которая содержит входные пользовательские данные.

Напишите код, который конвертирует значение строки `message` из **(#1)** в **(#2)** и записывает результат в переменную `result`.

**(#1)** - `tagname#id.class1.class2.classN`

**(#2)** - `<tagname id="id" class="class1 class2 classN"></tagname>`

**Подсказка!** Для разработки и отладки регулярных выражений используйте: [https://regex101.com](https://regex101.com/)

**Sample Input 1:**

```
div#app.vue
```

**Sample Output 1:**

```
<div id="app" class="vue"></div>
```

**Sample Input 2:**

```
div#button.primary
```

**Sample Output 2:**

```
<div id="button" class="primary"></div>
```