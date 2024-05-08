---
route: /api/login
icon: chevron-right
---

# POST /login
Авторизоваться стандартным способом

Тело запроса в JSON:
```
{
    "username": "Coaf",
    "password": "test"
}
```

Пример положительного ответа:
```
Устанавливает куки "JSESSIONID" и "remember-me"
Возвращает код 200
```

```
{
    "success": true
}
```