# NODA — Web

Фронтенд для Q&A-платформи NODA. Побудовано на **Next.js 14** з App Router.

---

## Технології

| Компонент | Технологія |
|---|---|
| Фреймворк | Next.js 14 (App Router) |
| Мова | TypeScript |
| Стилізація | Tailwind CSS / PostCSS |
| Пакетний менеджер | pnpm |
| Лінтер / форматер | ESLint + Prettier |

---

## Запуск

```bash
# Встановлення залежностей
pnpm install

# Режим розробки
pnpm dev

# Продакшн-збірка
pnpm build
pnpm start
```

Застосунок доступний за адресою `http://localhost:3000`

Необхідні змінні середовища (`.env.local`):
```env
NEXT_PUBLIC_API_URL=http://localhost:3001
```

---

## Пов'язані репозиторії

- [NODA API](https://github.com/Ripper-del/UNIFORM-API) — бекенд на NestJS
