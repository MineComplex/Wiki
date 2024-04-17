---
route: /api/user/friends
icon: chevron-right
---

# GET /user/:id/friends
Получить список друзей игрока

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
    "friends": [
        {
            "id": "skiddgoddamn",
            "username": "SkiddGoddamn",
            "rank": "admin",
            "lastSeen": 1696022156992,
            "playTime": 2341231
        },
        {
            "id": "ahapxict",
            "username": "AHAPXICT",
            "rank": "admin",
            "lastSeen": 1696022210042,
            "playTime": 345521
        }
    ]
}
```
