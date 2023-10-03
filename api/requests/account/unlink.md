---
route: /api/account/unlink-social-media
icon: chevron-right
---

# POST /account/unlink
Отвязывает аккаунт от указанной соц. сети

Требуется валидный токен в заголовках запроса.

Тело запроса в JSON:
```
{
    "type": "VK"
}
```

Пример ответа:
```
{
    "type": "VK",
    "user": 460100799
}
```
