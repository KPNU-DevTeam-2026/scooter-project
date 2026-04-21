# 🌀 MATHMAZE: Cloud-Driven Educational Ecosystem

![License: Unlicense](https://img.shields.io/badge/license-Unlicense-blue.svg)
![Build: Passing](https://img.shields.io/badge/Build-Passing-brightgreen.svg)
![Platform: WebGL](https://img.shields.io/badge/Platform-Unity_WebGL-orange.svg)
![Language: C#](https://img.shields.io/badge/Language-C%23-green.svg)

## 📖 Опис проєкту
**MATHMAZE** — це інноваційний навчальний вебсимулятор, що перетворює вивчення математики на імерсивний ігровий досвід. На відміну від статичних онлайн-тестів, наш проєкт пропонує динамічне 3D-середовище лабіринту, де кожна перешкода — це математична задача.

### Яку проблему ми вирішуємо?
* **Низька залученість:** Ми долаємо бар'єр абстрактності математики через гейміфікацію (RPG-механіки, магазин, бустери).
* **Статичність контенту:** Завдяки NoSQL архітектурі, вчитель може змінювати параметри рівнів у хмарі без необхідності перезбірки гри.
* **Академічна доброчесність:** Вбудована система Anti-cheat моніторить активність ігрової сесії, запобігаючи використанню стороннього ПЗ.

---

## 📂 Структура проєкту
Відповідно до архітектури рішення, репозиторій має наступну структуру:
* `/src` — Вихідний код проєкту (Unity скрипти, GameBridge JS).
* `/docs` — Технічна документація, схеми бази даних та UML-діаграми.
* `/tests` — Модульні тести для перевірки логіки Anti-cheat.

---

## 🛠 Технологічний стек
Проєкт побудований на базі сучасних інструментів розробки та хмарних сервісів:

* **Frontend (Game Engine):** [Unity](https://unity.com/) (C#) — ядро ігрової логіки та рендеринг WebGL.
* **Web-Layer:** HTML5, CSS3, JavaScript (ES6+).
* **Backend & Cloud:** [Firebase](https://firebase.google.com/) (Cloud Firestore, Auth, Hosting).
* **Middleware:** **GameBridge JS** — авторський модуль для асинхронного зв'язку між Unity та хмарною базою даних.

---

## 🚀 Інструкція із запуску (Installation)

Щоб запустити проєкт локально для розробки, виконайте наступні кроки:

1. **Клонуйте репозиторій:**
   ```bash
   git clone [https://github.com/KPNU-DevTeam-2026/scooter-project.git](https://github.com/KPNU-DevTeam-2026/scooter-project.git)
   cd scooter-project
2. **Відкрийте проєкт**
Запустіть Unity Hub та додайте папку проєкту (директорія src) для роботи з Unity WebGL.

## ⚖️ Ліцензія (Legal Note)
Цей проєкт розповсюджується під ліцензією Unlicense. Ми обрали її, оскільки MATHMAZE — це навчальний проєкт, і ми хочемо, щоб наш код був максимально доступним для спільноти без жодних юридичних обмежень.

## 👥 Команда проєкту
Данильчук Андрій — Tech Lead (Створення організації, налаштування Git та захист гілок).

Левчук Владислав — Legal Officer (Вибір та налаштування LICENSE, Legal Note).

Білоус Ілля — Content Creator / Dev (Оформлення README, Badges, структура репозиторію).
