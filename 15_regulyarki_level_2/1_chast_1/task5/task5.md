У вас есть переменная `text`, которая содержит входные пользовательские данные.

Напишите код, который конвертирует инлайн markdown текст из переменной `text` в html и записывает результат в переменную `result`.

Реализуйте поддержку следующих тегов:

```markdown
**bold** => <strong>bold</strong> 

_italic_ => <em>italic</em>

[link](https://www.example.com) => <a href="https://www.example.com">link</a>
                  
```

**Подсказка!** Для разработки и отладки регулярных выражений используйте: [https://regex101.com](https://regex101.com/) 

**Sample Input 1:**

```
**Жирный** текст
```

**Sample Output 1:**

```
<strong>Жирный</strong> текст
```

**Sample Input 2:**

```
Перейти на [сайт](https://www.example.com)
```

**Sample Output 2:**

```
Перейти на <a href="https://www.example.com">сайт</a>
```

**Sample Input 3:**

```
_Другой_ текст
```

**Sample Output 3:**

```
<em>Другой</em> текст
```