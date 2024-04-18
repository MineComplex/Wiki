---
route: /api/account/get-profile
icon: chevron-right
---

# GET /account/
Получить аккаунт

Требуется авторизация.

Пример ответа:
```
{
    "id": "coaf",
    "username": "Coaf",
    "socials": {
        "discord": 427505684230307850
    },
    "totp": "discord",
    "rank": "owner",
    "balance": 31340.80999999985,
    "lastSeen": 1713282334588,
    "registeredAt": 1709386444602
}
```
