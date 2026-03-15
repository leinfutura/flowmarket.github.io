# Flower Marketplace 
Проект создан по спецификации маркетплейса доставки цветов. В репозитории есть фронтенд на Next.js и бэкенд на Node.js (Express + Socket.IO) с мок-данными.

## Структура
- frontend — витрина и пользовательские страницы
- backend — API + realtime чат (заготовка)
- docs — копия спецификации

## Быстрый старт

### Фронтенд
```
cd frontend
npm install
npm run dev
```

### Бэкенд
```
cd backend
npm install
npm run dev
```

## Маршруты (ключевые)
- `/` — главная
- `/bouquets` — каталог
- `/bouquets/[category]` — категория
- `/shops/[shop]` — магазин
- `/cart` — корзина
- `/checkout` — оформление
- `/account` — личный кабинет клиента
- `/florist` — кабинет флориста
- `/reviews` — рейтинги и отзывы
- `/faq`, `/contacts`, `/promos`
- `/[city]` — гео-страницы
- `/[city]/bouquets/[category]` — SEO-варианты

Примечание: данные моковые, их можно заменить на реальные источники.
