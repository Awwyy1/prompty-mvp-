# Prompty MVP

## Запуск локально
1. `npm install`
2. Создайте `.env.local`:
```
OPENAI_API_KEY=sk-...
OPENAI_MODEL=gpt-4o-mini
```
3. `npm run dev`

## Деплой
- Рекомендуется Vercel. Импортируйте репозиторий, добавьте `OPENAI_API_KEY` в Project Settings → Environment Variables → Deploy.

## Функции MVP
- Генерация 2–3 вариантов промптов по теме.
- Переключатели: язык, цель, тон, глубина.
- Копирование результата.
