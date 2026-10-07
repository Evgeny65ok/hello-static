# Hello Static — CI/CD на GitHub Pages

Учебный проект: статический сайт (HTML + CSS + JS), автоматически публикуемый на GitHub Pages через GitHub Actions.

## 📸 Скриншоты

### 1. Открытый сайт на GitHub Pages
<img width="1610" height="873" alt="Снимок экрана 2026-10-07 105153" src="https://github.com/user-attachments/assets/dded55da-514c-4cda-84b1-f6c453b68626" />


### 2. GitHub Actions — успешный деплой
<img width="1722" height="662" alt="Снимок экрана 2026-10-07 105205" src="https://github.com/user-attachments/assets/ee2bd3ad-eab3-4c5f-b89c-459fd6a0f8cc" />


### 3. Настройки Pages (Source: GitHub Actions)
<img width="1748" height="976" alt="Снимок экрана 2026-10-07 105128" src="https://github.com/user-attachments/assets/11d1d30e-c65b-442a-857a-a20142139cc0" />


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
