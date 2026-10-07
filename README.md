# Hello Static — CI/CD на GitHub Pages

Учебный проект: статический сайт (HTML + CSS + JS), автоматически публикуемый на GitHub Pages через GitHub Actions.

## 📸 Скриншоты

### 1. Открытый сайт на GitHub Pages
![Site](site.png)

### 2. GitHub Actions — успешный деплой
![Actions](actions.png)

### 3. Настройки Pages (Source: GitHub Actions)
![Pages Settings](pages-settings.png)

## 🌐 Сайт

Открыть: https://evgeny65ok.github.io/hello-static/

## 📂 Структура

hello-static/
├── .github/workflows/ci-cd.yml
├── public/
│   ├── index.html
│   ├── style.css
│   └── script.js
└── README.md

## 🔁 CI/CD

- Push в main → GitHub Actions деплоит public/ на Pages
- Автоматическая публикация через actions/deploy-pages@v4

## 👤 Автор

Evgeny65ok
