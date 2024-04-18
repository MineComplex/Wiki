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
Устанавливает куки "JSESSIONID"
Возвращает код 200
```
