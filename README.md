# CRYENGINE V Manual — Offline Reader

Автономная офлайн-читалка документации **CRYENGINE V Manual** с полным русским переводом.
Offline CRYENGINE V Manual reader with a full Russian translation.

---

## Как пользоваться / How to use

1. Скачайте репозиторий (клонируйте или скачайте архив).
   Download the repository (clone it or download the archive).

2. Откройте файл **`viewer/index.html`** в браузере (Chrome, Edge, Firefox).
   Open **`viewer/index.html`** in a browser (Chrome, Edge, Firefox).

3. Слева — меню со всеми разделами, справа — текст статьи.
   Left — menu with all sections, right — the article text.

Никакой установки и интернета не требуется — всё работает локально.
No installation or internet connection required — everything runs locally.

---

## Двуязычность / Bilingual

Читалка содержит английские оригиналы (`viewer/pages/`) и русский перевод
(`viewer/pages-ru/`). Всё переключается внутри интерфейса.

The reader contains the English originals (`viewer/pages/`) and the Russian
translation (`viewer/pages-ru/`). Everything is switched inside the interface.

### Переключение языка / Language switch

- **В статье** (вверху справа) — кнопка `RU` / `EN`. Она показывает **текущий**
  язык; нажмите, чтобы открыть ту же статью на другом языке.
  **In an article** (top right) — the `RU` / `EN` button. It shows the **current**
  language; click it to open the same article in the other language.

- **В главном окне** (шапка, справа) — кнопка `RU` / `EN` переключает язык всего
  дерева меню и поиска.
  **In the main window** (header, right) — the `RU` / `EN` button switches the
  language of the whole menu tree and search.

Выбранный язык и состояние меню запоминаются в браузере.
The chosen language and menu state are remembered by the browser.

### Поиск / Search

Строка поиска в шапке ищет по заголовкам **на обоих языках** — можно вводить как
русские, так и английские названия.
The search box in the header searches titles in **both languages** — you can type
either Russian or English names.

---

## Что внутри / What's included

| | |
|---|---|
| `viewer/index.html` | Точка входа — главная страница читалки / Entry point — reader home |
| `viewer/pages/` | Английские статьи (1722) / English articles (1722) |
| `viewer/pages-ru/` | Русский перевод (1722) / Russian translation (1722) |
| `viewer/pdf-ru/` | Документы PDF, переведённые на русский / PDF documents translated to Russian |
| `viewer/attachments/` | Картинки, видео и прочие вложения / Images, videos and other attachments |

В меню также есть ветки **«PDF гайды»** и **«AI документы»** — переводы отдельных
документов, которые в оригинале были PDF/DOC/PPT.
The menu also has **«PDF Guides»** and **«AI Documents»** branches — translations
of separate documents that were originally PDF/DOC/PPT.

---

## Скриншот / Screenshot

Открытие статьи на русском / Opening an article in Russian:

```
CRYENGINE V Руководство   [ Поиск по названиям... ]        [RU] [≡]
├─ PDF гайды
│   ├─ Модульное дерево поведения
│   └─ ...
├─ AI документы
└─ CRYENGINE – Начало работы
        ← Содержание   Обзор системы ИИ            [EN]
        ┌────────────────────────────────────────────┐
        │ Обзор системы ИИ                           │
        │ Навигационная система по умолчанию ...     │
        └────────────────────────────────────────────┘
```

---

## Сведения / Notes

- Документация является собственностью Crytek; репозиторий приватный и предназначен
  для личного использования.
  The documentation is property of Crytek; the repository is private and intended
  for personal use.
- Русский перевод сделан автоматически с сохранением терминологии (имена классов,
  ключи, идентификаторы не переводились).
  The Russian translation was done automatically with terminology preserved
  (class names, keys and identifiers were not translated).
