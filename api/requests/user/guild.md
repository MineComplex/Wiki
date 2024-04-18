---
route: /api/user/get-user-guild
icon: chevron-right
---

# GET /user/:id/guild
Получить банду игрока

Пример ответа:
```
{
    "user": {
        "id": "coaf",
        "username": "Coaf",
        "rank": "owner",
        "lastSeen": 1696251716151,
        "playTime": 6217111
    },
    "guild": {
        "name": "Админская",
        "prefix": "777",
        "color": "&4",
        "description": "Оффициальная админская банда",
        "createdAt": 1696251636727
    }
}
```
