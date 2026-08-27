# Таня та Саша — wedding invitation

Готовий статичний сайт для GitLab Pages із вбудованою RSVP-формою.

## RSVP

Форма вже підключена до Google Apps Script:

`https://script.google.com/macros/s/AKfycbyJWucqEG3cqZcBhbrhrapj48MuHrAGnohoVTGswOqVnD0EsWq2oQZqauDWy5O2HoYcXw/exec`

Поля, які надсилаються:
- `name`
- `ceremony`
- `dinner`
- `comment`

## GitLab Pages

1. Завантажте всі файли в корінь GitLab repository.
2. Commit у default branch.
3. Дочекайтесь успішного pipeline.
4. Відкрийте **Deploy → Pages**.

## Важливо

Google Apps Script має бути розгорнутий як **Web app**:
- Execute as: Me
- Who has access: Anyone

У таблиці має бути аркуш з тією назвою, яка вказана у вашому Apps Script.
