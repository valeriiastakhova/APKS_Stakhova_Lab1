# AI Agent CI/CD Automation

Виконала: Стахова Валерія
Група: КІ-406
Варіант: 6 (TypeScript, npm scripts, Vitest)

## Опис проєкту
Цей репозиторій містить AI-агента, який автоматично генерує кросплатформний Hello World проєкт на TypeScript, налаштовує систему збірки через npm scripts, створює юніт-тести на базі Vitest та генерує GitHub Actions workflow для CI на Windows, Linux та macOS.

## Запуск агента
Для автоматичної генерації проєкту та налаштування CI/CD використовувався GitHub Copilot Chat. 

**Кроки для запуску:**
1. Відкрити панель GitHub Copilot Chat у VS Code.
2. Прикріпити маніфест агента та оркестратор, додавши в контекст чату файли `#build-engineer.agent.md` та `#init.prompt.md`.
3. Агент автоматично розпізнає завдання (Identifying project setup tasks) і покроково запросить дозволи на створення необхідних файлів (package.json, tsconfig.json, тести, workflow).

## Локальна перевірка
Щоб перевірити згенерований код локально, виконайте:
1. `npm install` — встановлення залежностей.
2. `npm run build` — компіляція TypeScript у JavaScript.
3. `npm run test` — запуск юніт-тестів (Vitest).

