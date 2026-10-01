# Maison Dorée – онлайн магазин за парфюми и козметика

Статичен сайт (HTML + CSS + JavaScript), без инсталации.

## Как да го качиш в GitHub и да е онлайн (GitHub Pages)
1. Влез в github.com → New repository → име `maison-doree` → Create repository.
2. Натисни „uploading an existing file“ и качи `index.html` и папката `images` (всичко от тази папка).
3. Commit changes.
4. Settings → Pages → Source: „Deploy from a branch“ → Branch: `main` / `(root)` → Save.
5. След 1–2 минути сайтът е на `https://ТВОЕТО-ИМЕ.github.io/maison-doree/`.

## Как да редактираш
- Продуктите са в `index.html`, в `const D=`...``: всеки ред е `Подкатегория|Марка|Име|Цена в €|цвят|име-на-снимка`.
- Снимките са в `images/` (името без .jpg е последното поле на реда).
- Отстъпката (10% над 150 €) е във функция `disc()`.
