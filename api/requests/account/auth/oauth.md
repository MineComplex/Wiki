---
route: /api/oauth
icon: chevron-right
---

# GET /oauth2/authorization/:type
Авторизоваться через соц. сеть

Виды соц. сетей:
- vk
- discord

Пример положительного ответа:
```
Устанавливает куки "JSESSIONID" и "remember-me"
Редиректит на https://minecomplex.net/account
```

Пример отрицательного ответа:
```
Редиректит на https://minecomplex.net/play?error=user_not_found
```

