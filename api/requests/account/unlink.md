---
route: /api/account/unlink-social-media
icon: chevron-right
---

# POST /account/unlink
Отвязывает аккаунт от указанной соц. сети

Требуется авторизация.

Тело запроса в JSON:
```
{
    "type": "VK"
}
```

Пример положительного ответа:
```
{
    "requiredVerification": true
}
```
