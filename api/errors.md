---
title: "Ошибки"
icon: lock
---

Пример ответа с ошибкой:
```
{
    "error": {
        "code": 2,
        "message": "You must log in before do this"
    }
}
```

{.compact}
Код   | Причина
---    | ---
-3 | Неизвестная ошибка
-2 | Ошибка сервера
-1 | Неизвестный метод
1 | Превышен лимит запросов
2 | Не авторизован
3 | Неправильный пароль или пользователь
4 | Необходим код двух-факторной авторизации
8 | Неправильные указанные параметеры
9 | Отключенный метод
10 | Обьект не найден. 404