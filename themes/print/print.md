# Версия для печати

Кроме медиа-запроса `print` для оптимизации сайтов для печати можно использовать css-свойства:

1. Item 1
1. Item 2
1. Item 3


- [page-break-before](http://www.w3schools.com/cssref/pr_print_pagebb.asp)
- [page-break-after](http://www.w3schools.com/cssref/pr_print_pageba.asp)
- [page-break-inside](http://www.w3schools.com/cssref/pr_print_pagebi.asp)

## Примеры

```css
h2 {
	page-break-before: always;
}
```
в данном случае перед каждым h2 будет вставлен разрыв страницы,	чтобы заголовок переходил на новую страницу.
