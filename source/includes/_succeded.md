# Токенизация

## Статус коды успеха

| Статус код | Значение             |
| ---------- | -------------------- |
| 200        | Токен успешно создан |
| 202        | Запрос принят к обработке, но результат его обработки еще неизвестен |

## Типы

| Тип                    | Значение  |
| ---------------------- | --------- |
| payment_token_created  | Токен успешно создан |

## Формат выдачи токена

```js
{
    message: 'Токен для оплаты создан',
    status_code: 200,
    type: 'payment_token_created',
    response: {
        paymentToken: <string>
    }
}
```