---
route: /api/account/orders
icon: chevron-right
---

# GET /account/orders
Получить историю покупок в донат магазине

Требуется авторизация.

Тело запроса в JSON:
```
[
    {
        "method": "FREEKASSA",
        "category": "ranks",
        "product": "sapphire",
        "amount": 1499.99,
        "createdAt": 1713427953994,
        "paidAt": 171342790000,
        "refundedAt": null
    }
]
```