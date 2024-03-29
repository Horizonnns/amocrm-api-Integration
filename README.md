# amoCRM API Интеграция

Этот проект демонстрирует интеграцию с API amoCRM для получения и отображения данных о сделках.

## Основные функции

- Получение данных о сделках с помощью API amoCRM
- Отображение данных о сделках в таблице
- Пагинация данных (2, 5, 10 сделок на странице)
- Сортировка данных по бюджету и названию сделки
- Автоматическое обновление access_token по истечении его срока действия

## Настройка конфигурации

1. Измените параметры файл `config.js` на свои

```config.js:
CLIENT_ID=Ваш_client_id
CLIENT_SECRET=Ваш_client_secret
REDIRECT_URI=Ваш_redirect_uri
AUTHORIZATION_CODE=Ваш_authorization_code

## Использование

1. Клонируйте репозиторий
2. Установите зависимости с помощью `npm install`
3. Запустите проект с помощью `npm run dev`
4. Откройте в браузере `http://localhost:5050`

## Требования

- Node.js
- npm

## Лицензия

MIT
