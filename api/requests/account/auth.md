---
route: /api/account/auth
icon: chevron-right
---

# POST /account/auth

Параметер code является кодом от двух-факторной авторизации,
который вслучае попытки логина высылается игроку в указанную им соц. сеть.

Если игрок не имеет ни одной привязанной соц. сети, то параметер code 
- необязателен.

Тело запроса в JSON:
```
{
    "username": "coaf",
    "password": "123123",
    "code": "AkeMwA"
}
```

Пример ответа:
```
{
    "token": "TOKEEEEEEN",
    "user": {
        "id": "coaf",
        "username": "Coaf",
        "rank": "owner",
        "lastSeen": 1696022430112,
        "registeredAt": 1695657313064,
        "gems": 0.0
    }
}
```
