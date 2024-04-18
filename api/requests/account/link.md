---
route: /api/account/link-social-media
icon: chevron-right
---

# POST /account/link
Привязать аккаунт к соц. сети

Требуется авторизация.

Тело запроса в JSON:
```
{
    "code": "A83kAMz"
}
```

Пример положительного ответа:
```
{
    "type": "VK",
    "user": 460100799
}
```
