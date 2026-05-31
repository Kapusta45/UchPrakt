Архевированную папку нужно распокавать в удобном месте и запустить файл TicketSupportSystem.sln
# Система учета обращений в техподдержку

## Описание
Приложение для учета обращений пользователей в службу технической поддержки.

## Технологии
- C# .NET 10.0
- ASP.NET Core Web API
- Windows Forms
- System.Text.Json

## Функционал
- Просмотр списка обращений
- Добавление нового обращения
- Изменение статуса (New → InProgress → Resolved → Closed)
- Удаление обращения
- Сохранение данных в JSON-файл

## Запуск проекта
1. Запустить TicketApi
2. Запустить TicketApp.UI через "ПКМ → Отладка → Новый экземпляр"

## API Endpoints
- GET    /api/tickets
- GET    /api/tickets/{id}
- POST   /api/tickets
- PUT    /api/tickets/{id}
- PUT    /api/tickets/{id}/status
- DELETE /api/tickets/{id}
