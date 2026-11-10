# Litex Vanilla+ | Wiki

Официальная энциклопедия уютного Vanilla+ сервера **Litex** (Season I) на базе [VitePress](https://vitepress.dev).

🌐 **Вики:** https://kotmir.github.io/litex-wiki/

## О сервере

- **IP:** `mc.litex.tech`
- **Версия:** Java 26.2
- **Старт сезона:** 19.09.2026
- **Сайт:** [litex.tech](https://litex.tech)
- **Discord:** [discord.gg/litex](https://discord.gg/litex)

## Локальный запуск

```bash
npm install
npm run docs:dev      # режим разработки
npm run docs:build    # сборка
npm run docs:preview  # предпросмотр сборки
```

Требуется Node.js 22 или новее.

## Структура

```
docs/
├── .vitepress/
│   ├── config.mts    # конфигурация сайта
│   └── theme/        # тема (custom.css, index.ts)
├── index.md          # главная
├── start.md          # как начать играть
├── info.md           # о сервере и границы миров
├── mods.md           # моды и сборка
├── rules.md          # правила
└── links.md          # ссылки и ресурсы
```

## Деплой

Сайт автоматически собирается и публикуется на GitHub Pages при каждом пуше в ветку `main` (см. `.github/workflows/deploy.yml`).
