# Китобҳо / Textbooks

## Файлы раздела

- `books.html` — список учебников
- `book-viewer.html` — просмотр PDF + оглавление + поиск по темам
- `js/books-data.js` — каталог книг и TOC

## PDF-файлы (нужно загрузить вручную)

Из-за размера (~20 МБ) PDF не пушатся через API. Загрузите их через веб-интерфейс GitHub:

1. Откройте репозиторий → **Add file** → **Upload files**
2. Создайте папку `books/` (или зайдите в неё)
3. Загрузите:
   - `ximiya-8.pdf` — Химия 8 класс
   - `ximiya-9.pdf` — Химия 9 класс

Или через git:

```bash
git clone https://github.com/ssohibov945-create/chemistry-elements.git
cd chemistry-elements
mkdir -p books
# скопируйте PDF в books/
git add books/
git commit -m "Add chemistry textbooks PDF"
git push
```

После загрузки PDF раздел «Китобҳо» будет полностью работать: открытие книги, поиск темы, переход на страницу.
