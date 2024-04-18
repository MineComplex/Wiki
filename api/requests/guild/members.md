---
route: /api/guild/get-members
icon: chevron-right
---

# GET /guild/:query/members
Получить список участников банды

Тело запроса в JSON:
```
{
    "guild": {
        "name": "Админская",
        "prefix": "777",
        "color": "&4",
        "description": "Оффициальная админская банда",
        "createdAt": 1696251636727
    },
    "members": [
        {
            "id": "coaf",
            "name": "Coaf",
            "rank": "LEADER",
            "donated": 234.0,
            "entered": 1713272483275
        },
        ...
    ]
}
```