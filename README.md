# Портфолио

Это проект портфолио, созданный с использованием Nuxt 3 и Tailwind CSS. Здесь все обо мне

## Содержание

- [Установка](#установка)
- [Запуск](#запуск)
- [Реализованные функции](#реализованные-функции)
- [Структура проекта](#структура-проекта)
- [Используемые технологии](#используемые-технологии)

## Установка

Для начала клонируйте репозиторий и установите зависимости:

```sh
git clone https://github.com/ваш-логин/ваш-репозиторий.git
cd ваш-репозиторий
npm install
```

## Запуск

Для запуска проекта в режиме разработки используйте команду:

```sh
npm run dev
```

Для сборки проекта используйте команду:

```sh
npm run build
```

Для предварительного просмотра собранного проекта используйте команду:

```sh
npm run preview
```

## Реализованные функции

✅Темная и светлая тема с переключателем (components/Custom/ThemeSwitcher.vue)
⛔Переключатель языков (components/Custom/LangSwitcher.vue)

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

- [Nuxt 3](https://nuxt.com/)
- [Vue 3](https://vuejs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [TypeScript](https://www.typescriptlang.org/)
- [JavaScript]
