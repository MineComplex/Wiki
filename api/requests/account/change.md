---
route: /api/account/change-password
icon: chevron-right
---

# POST /account/change
Изменить пароль аккаунта

Требуется авторизация.

Тело запроса в JSON:
```
{
    "password": "newPassword"
}
```

Пример положительного ответа:
```
{
    "success": true
}
```
