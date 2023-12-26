---
route: /api/account/change-password
icon: chevron-right
---

# POST /account/change

Требуется валидный токен в заголовках запроса.

Тело запроса в JSON:
```
{
    "password": "newPassword"
}
```