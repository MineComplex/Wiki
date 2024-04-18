---
route: /api/user/get-user-stats
icon: chevron-right
---

# GET /user/:id/stats
Получить статистику игрока на всех режимах

Пример ответа:
```
{
    "user": {
        "id": "coaf",
        "username": "Coaf",
        "rank": "owner",
        "lastSeen": 1713385037514,
        "playTime": 1483
    },
    "stats": {
        "PRISON": {
            "raw_blocks_mined": 11400,
            "blocks_mined": 11400,
            "playtime": 178
        },
        "LOBBY": {
            "playtime": 981
        },
        "ANNI": {
            "wins": 1,
            "kills": 1,
            "games": 1,
            "wood": 12,
            "playtime": 2,
            "deaths": 3
        },
        "BUILD": {
            "playtime": 61
        },
        "GLOBAL": {
            "votes": 2,
            "playtime": 1483
        },
        "LIMBO": {
            "playtime": 261
        }
    }
}
```
