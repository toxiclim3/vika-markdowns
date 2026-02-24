## Ранкове посилання про погоду  

Ціль: Створити ШІ-агента, який надсилає користувачу вранці інформацію про сьогоднішню погоду  

Модель: OpenAI gpt-4o-mini

Інструмент: n8n

Промпт:
```Create a warm, cheerful good morning message in Ukrainian for Odessa, Ukraine based on this weather forecast data: {{ $('Get Weather Forecast').item.json.body }}. Start with "Доброго ранку!" and end with "Гарного дня!". Keep it friendly and concise. Write the entire message in Ukrainian language.```


