# Simple Site — Навчальний HTML/CSS Проєкт

## Опис

**Simple Site** — це навчальний проєкт, створений для практики семантичної HTML-розмітки, роботи з CSS та базової взаємодії з JavaScript.

Проєкт містить:

- адаптивну структуру сторінки;
- навігацію;
- секції контенту;
- кастомну кнопку запуску відео;
- використання Flexbox;
- стилізацію через CSS Variables;
- організацію стилів за методологією BEM.

---

## Використані технології

- HTML5
- CSS3
- JavaScript (Vanilla JS)
- Flexbox
- BEM Naming
- CSS Variables

---

## Структура проєкту

```text
project/
│
├── index.html
│
├── src/
│   ├── styles/
│   │   ├── reset.css
│   │   └── style.css
│   │
│   ├── images/
│   │   ├── Rectangle-5.webp
│   │   ├── coding.mp4
│   │   └── icons/
│   │       └── project.svg
│   │
│   └── fonts/
│       ├── Roboto-Regular.woff2
│       └── Roboto-Medium.woff2
│
└── README.md
```

---

## Основні можливості

### Навігація

- горизонтальне меню;
- активний пункт навігації;
- використання Flexbox.

### Header секція

- заголовок;
- текстовий опис;
- кнопка дії.

### About секція

- інформаційний блок про автора/проєкт.

### Projects секція

- список статистики проєктів;
- SVG-іконки через `::before`.

### Video секція

- HTML5 video;
- кастомна кнопка запуску;
- JavaScript для керування відтворенням.

### Footer

- інформація про автора;
- copyright.

---

## Особливості реалізації

### Семантична HTML-структура

У проєкті використовуються:

- `<header>`
- `<main>`
- `<section>`
- `<nav>`
- `<footer>`

---

### BEM Naming

Приклади класів:

```css
.projects__item
.process__container
.footer__copyright
```

---

### CSS Variables

```css
:root {
  --bg-color: #eeeff1;
  --black-color: #000000;
  --white-color: #ffffff;
  --brand-color: #34547a;
  --light-gray-color: #727272;
}
```

---

### Кастомна кнопка Play

Кнопка створена за допомогою:

- `position: absolute`
- псевдоелемента `::before`
- CSS border triangle technique

---

## Запуск проєкту

1. Завантажити або клонувати репозиторій.
2. Відкрити `index.html` у браузері.

---

## Мета проєкту

Проєкт створений для:

- практики HTML/CSS;
- вивчення Flexbox;
- роботи з BEM;
- практики адаптивної верстки;
- створення чистої структури проєкту.

---

## Автор

Навчальний проєкт виконаний для практики фронтенд-розробки.
