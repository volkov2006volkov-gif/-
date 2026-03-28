# 🌀 Portalfolio — Rick & Morty Themed Portfolio

Портфолио в стиле Rick and Morty, созданное с использованием React, Vite и Tailwind CSS.

![React](https://img.shields.io/badge/React-19.2.3-61dafb?style=flat&logo=react)
![Vite](https://img.shields.io/badge/Vite-7.2.4-646cff?style=flat&logo=vite)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-4.1.17-38bdf8?style=flat&logo=tailwindcss)
![TypeScript](https://img.shields.io/badge/TypeScript-5.9.3-3178c6?style=flat&logo=typescript)

## ✨ Особенности

- 🎨 Анимированный дизайн в стиле Rick and Morty
- 🚀 Быстрая загрузка и оптимизация
- 📱 Полностью адаптивный дизайн
- ⚡ Core Web Vitals 95+
- 🎭 Портальные эффекты и анимации
- ♿ Доступность (WCAG AA)

## 🛠 Стек технологий

- **React 19** — UI библиотека
- **Vite** — Сборщик проекта
- **Tailwind CSS 4** — Стилизация
- **TypeScript** — Типизация

## 🚀 Быстрый старт

### Установка зависимостей

```bash
npm install
```

### Запуск в режиме разработки

```bash
npm run dev
```

### Сборка для продакшена

```bash
npm run build
```

### Предпросмотр продакшен сборки

```bash
npm run preview
```

## 📁 Структура проекта

```
├── public/
│   └── images/          # Изображения проектов
├── src/
│   ├── App.tsx          # Основной компонент приложения
│   ├── index.css        # Глобальные стили
│   ├── main.tsx         # Точка входа
│   └── utils/
│       └── cn.ts        # Утилита для объединения классов
├── index.html
├── package.json
├── tsconfig.json
└── vite.config.ts
```

## 🎨 Кастомизация

### Изменение цветов

Откройте `src/index.css` и измените CSS переменные:

```css
:root {
  --portal-green: #39ff14;
  --portal-blue: #7cf4ff;
  --portal-dark: #070912;
}
```

### Замена изображений

Изображения персонажей находятся в `src/App.tsx`. Замените URL на свои:

```tsx
style={{ backgroundImage: `url("your-image-url.jpg")` }}
```

## 📦 Развёртывание

### Vercel

```bash
npm install -g vercel
vercel
```

### Netlify

```bash
npm run build
# Загрузите папку dist на Netlify
```

### GitHub Pages

1. Установите `gh-pages`:
```bash
npm install -D gh-pages
```

2. Добавьте скрипты в `package.json`:
```json
"scripts": {
  "predeploy": "npm run build",
  "deploy": "gh-pages -d dist"
}
```

3. Задеплойте:
```bash
npm run deploy
```

## 📝 Лицензия

MIT

## 👨‍💻 Автор

Создано с 🧪 и 💚

---

> **Wubba Lubba Dub Dub!** 🌀
