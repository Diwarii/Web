# Знакомство со стеком React, Next.js, TanStack Query, SQLite

## Файловый раутинг Next.js - работает из папки src/app

[читать по ссылке](docs/next-routing.md)


## Назначение файлов

### Приложение - Frontend

- Главный шаблон (точка входа) - [src/app/layout.tsx](src/app/layout.tsx)
- Компоненты шаблона - [src/app/components/layout](src/app/components/layout)
- Страница - [src/app/groups/page.tsx](src/app/groups/page.tsx)
- Компонент - [src/components/Groups/Groups.tsx](src/components/Groups/Groups.tsx)
- Хук получения данных - [src/hooks/useGroups.tsx](src/hooks/useGroups.tsx)
- Получение данных из API - [src/api/groupsApi.ts](src/api/groupsApi.ts)

### API - Backend

- API возвращает список групп - [src/app/groups/route.ts](src/app/groups/route.ts)
- Запрос к БД - [src/db/groupDb.ts](src/db/groupDb.ts)
- Стартовая БД и запросы - папка db в корне проекта

## Инструменты
- ### [TanStackQuery - работа с данными в приложении](docs/tanstack-query.md)
- ### [БД SQLite](docs/db.md)
- ### [HTTP запросы](docs/http.md)
- ### [GIT](docs/git.md)

## SSR - Server Side Rendering, передача состояния на клиент
[читать по ссылке](docs/ssr.md)


## Ссылки

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
  
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

- TanStackQuery - https://tanstack.com/query/latest

- https://nextjs.org/docs/app/api-reference/file-conventions/route

