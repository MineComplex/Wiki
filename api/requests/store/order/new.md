---
route: /api/store/create-order
icon: chevron-right
---

# POST /store/order/new
Создать заказ

Тело запроса в JSON:
```
{
    "product": "sapphire",
    "username": "Coaf",
    "email": "sigamatute@gmail.com",
    "coupon": "2024",
    "method": "FREEKASSA" 
}
```

Пример положительного ответа:
```
{
    "order": "uuid",
    "url": "https://pay.freekassa.ru/...",
    "payment": "https://minecomplex.net/order/uuid"
}
```
