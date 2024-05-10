---
route: /api/account/change-password
icon: chevron-right
---

# POST /account/change
Изменить пароль аккаунта.
Если аккаунт имеет привязку, то мы требуем
подтверждения игрока через бота.

Требуется авторизация.

Тело запроса в JSON:
```
{
    "oldPassword": "12345",
    "newPassword": "123123"
}
```

Пример положительного ответа:
```
{
    "requiredVerification": true/false
}
```
