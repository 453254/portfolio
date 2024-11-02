# Портфолио

Это проект портфолио, созданный с использованием Nuxt 3 и Tailwind CSS. Здесь все обо мне

## Содержание

- [Установка](#установка)
- [Запуск](#запуск)
- [Реализованные функции](#реализованные-функции)
- [Структура проекта](#структура-проекта)
- [Используемые технологии](#используемые-технологии)
- [В будующем](#в-будующем)

## Установка

Для начала клонируйте репозиторий и установите зависимости:

```sh
git clone https://github.com/453254/portfolio.git
cd portfolio
```

```sh
npm install
npx nuxi module add @nuxtjs/tailwindcss
npx tailwindcss init
```

```sh
npm run dev
```

## Запуск

Для запуска проекта в режиме разработки используйте команду:

```sh
npm run dev
```

Для сборки статичного проекта используйте команду:

```sh
npm run build
```

Для предварительного просмотра собранного проекта используйте команду:

```sh
npm run preview
```

## Реализованные функции

- **Переключатель тем**: Возможность переключаться между светлой и темной темами.
- **Переключатель языков**: Возможность выбирать язык интерфейса. (реализован только переключатель)
- **Карточки навыков**: Отображение моих навыков с использованием иконок.
- **Ссылки на социальные сети**: Быстрый доступ к моим профилям в социальных сетях, таких как Telegram и GitHub.


## Структура проекта

```
└── 📁portfolio
    └── 📁.git
    └── 📁.nuxt
    └── 📁assets
        └── 📁css
            └── custom.css
            └── main.css
            └── themeswitcher.css
        └── 📁image
            └── cursor.cur
            └── profile-photo.jpg
        ├── sound
    └── 📁components
        └── 📁Custom
            └── 📁SkillList
                └── SkillCard.vue
                └── SkilsList.vue
            └── Button1.vue
            └── GitHubLink.vue
            └── LangSwitcher.vue
            └── TGLink.vue
            └── ThemeSwitcher.vue
        └── 📁Main
            └── Footer.vue
        └── ButtonsCard.vue
        └── ProfileCard.vue
    └── 📁layouts
        └── default.vue
    └── 📁pages
        └── index.vue
    └── 📁public
        └── favicon.ico
        └── robots.txt
    └── 📁server
        └── tsconfig.json
    └── .gitignore
    └── app.vue
    └── nuxt.config.ts
    └── package-lock.json
    └── package.json
    └── README.md
    └── tailwind.config.js
    └── tsconfig.json
```

## Используемые технологии

- [Nuxt 3](https://nuxt.com/) - Фреймворк для создания серверных приложений на Vue.js.
- [Vue 3](https://vuejs.org/) - Прогрессивный фреймворк для создания пользовательских интерфейсов.
- [Tailwind CSS](https://tailwindcss.com/) - Утилитарный CSS-фреймворк для стилизации.
- [TypeScript](https://www.typescriptlang.org/) - язык программирования на основе JavaScript 

## В будующем

Добавить карточку со сделанными проектами
