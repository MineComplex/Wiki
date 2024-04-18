---
route: /api/account/punishments
icon: chevron-right
---

# GET /account/punishments
Получить историю наказаний игрока

Требуется авторизация.

Тело запроса в JSON:
```
[
    {
        "id": "7b0fffca-69bb-4267-a3ce-fb6f4d828fc7",
        "type": "ban",
        "issuer": "Coaf",
        "reason": "читы",
        "issuedAt": 1713427953994,
        "expiresAt": null,
        "active": true
    }
]
```