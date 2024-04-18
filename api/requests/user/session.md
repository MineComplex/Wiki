---
route: /api/user/get-user-current-session
icon: chevron-right
---

# GET /user/:id/session
Получить текущую сессию игрока

Пример ответа:
```
{
    "user": {
        "id": "coaf",
        "username": "Coaf",
        "rank": "owner",
        "lastSeen": 1696022430112,
        "playTime": 6104650
    },
    "session": {
        "online": true,
        "server": "LOBBY_1",
        "status": "Сидит в Лобби"
    }
}
```
