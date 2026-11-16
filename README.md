# Keepsake — Responsive Landing Page

Адаптивна верстка односторінкового лендінгу дизайн-агенції **Keepsake** за макетом Figma (`Desktop - 1280`, `Tablet - 768`, `Mobile - 375`, `Mobile - menu open`, `UI states`).

## Демо
- **GitHub Pages:** https://<samanykvolodymyr-max>.github.io/landing-keepsake/

## Технології та реалізовані рішення
- **Семантичний HTML5:** використано `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`, `<form>`, один `<h1>` на сторінку та логічну ієрархію заголовків.
- **Mobile First CSS & Design Tokens:** базові стилі від `320px` (макет `375px`) з медіазапитами `min-width: 768px` та `min-width: 1280px`; максимальна ширина контенту `1100px`. Кольори, шрифти та відступи винесені в `:root`.
- **Flexbox та CSS Grid:** розкладка секцій побудована на Flexbox, а сітка карток портфоліо — на CSS Grid (`aspect-ratio`) без сторонніх UI-фреймворків.
- **Інтерактивність без JavaScript:** випадаюче мобільне меню (бургер/хрестик) та фільтрація портфоліо за категоріями реалізовані через `:checked ~`, а стани форми підписки (`default`, `focus`, `error`, `success`) — засобами HTML5-валідації та CSS (`:focus`, `:invalid`, `:target`).
- **Доступність та продуктивність:** інлайн-SVG іконки, підтримка клавіатурної навігації (`:focus-visible`), touch-цілі не менше `44×44 px`, графіка у форматі `WebP` з `loading="lazy"`.
