---
route: /api/store/get-order-price
icon: chevron-right
---

# POST /store/order/price
Получить конечную стоимость товара

Тело запроса в JSON:
```
{
    "product": "sapphire",
    "coupon": "2024",
    "method": "FREEKASSA" 
}
```

Пример положительного ответа:
```
{
    "price": 1499.99,
    "error": null
}
```
