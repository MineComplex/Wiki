---
route: /api/account/get-session-history
icon: chevron-right
---

# GET /account/sessions
Получить историю сессий аккаунта
Список сортируется автоматически по
последнему подключению на сервер

Требуется авторизация.

Тело запроса в JSON:
```
[
    {
        "ip": "127.0.0.1",
        "timestamp": 1713280490307
    },
    ...
]
```