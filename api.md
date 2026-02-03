# Пример API: Получение списка магазинов

## Запрос

```http
GET /retail HTTP/1.1
Host: eda.primer.ru
Accept: application/json
Authorization: Bearer <access_token>
```

## Ответ (успешный)

HTTP/1.1 200 OK
Content-Type: application/json; charset=utf-8
```json
{
  "screen_title": "Выберите магазин",
  "retail": [
    {
      "id": "1",
      "name": "METRO",
      "description": "Ближайшая доставка",
      "delivery_time": "сегодня 21:00–23:00",
      "accent_text": null,
      "logo_url": "https://cdn.petrushka-green.ru/partners/metro.png",
      "deeplink": "https://www.metro.ru/dostavka?ref=petrushka_green"
    },
    {
      "id": "2",
      "name": "Ашан",
      "description": "Ближайшая доставка",
      "delivery_time": "сегодня 18:00–20:00",
      "accent_text": null,
      "logo_url": "https://cdn.petrushka-green.ru/partners/auchan.png",
      "deeplink": "https://www.auchan.ru/dostavka?ref=petrushka_green"
    },
    {
      "id": "3",
      "name": "ВкусВилл",
      "description": "Быстрая доставка",
      "delivery_time": "сегодня",
      "accent_text": "от 20 до 60 минут",
      "logo_url": "https://cdn.petrushka-green.ru/partners/vkusvill.png",
      "deeplink": "https://www.vkusvill.ru/dostavka?ref=petrushka_green"
    },
    {
      "id": "4",
      "name": "ВИКТОРИЯ",
      "description": "Ближайшая доставка",
      "delivery_time": "сегодня 17:00–19:00",
      "accent_text": null,
      "logo_url": "https://cdn.petrushka-green.ru/partners/viktoria.png",
      "deeplink": "https://www.viktoria.ru/dostavka?ref=petrushka_green"
    }
  ]
}
