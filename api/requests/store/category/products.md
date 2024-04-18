---
route: /api/store/get-category-products
icon: chevron-right
---

# GET /store/category/:id/products
Получить список товаров указанной категории
Сортировка товаров - по стоимости

Пример ответа:
```
[
    {
        "id": "emerald",
        "title": "Эмеральд",
        "image": "/content/image/ranks/emerald.png",
        "description": [
            "Норм донат"
        ],
        "price": 5000.0
    },
    ...
]
```
