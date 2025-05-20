# Flagship Landing Page

💼 Одностраничный лендинг для промышленных поставок

Поставки под ключ от 14 дней: спиральные компрессоры, сварочная проволока, электронные модули.

---

## 🚀 Быстрый старт

1. Склонируйте репозиторий или скачайте ZIP:
   ```bash
   git clone https://github.com/alseptkg/flagship-landing.git
   cd flagship-landing
   ```

2. Запустите локально:
   ```bash
   python3 -m http.server
   # Перейдите в браузере на http://localhost:8000
   ```

3. Или просто откройте `index.html` в браузере.

---

## 📬 Telegram-интеграция

Заявки с формы отправляются прямо в Telegram:

- Бот: `@alseptkg_bot`
- Получатель: chat_id `125279912`
- API-интеграция активна, работает через `fetch()` в JavaScript

Для подключения своего бота замените в `index.html`:
```js
const token = 'YOUR_TOKEN';
const chatId = 'YOUR_CHAT_ID';
```

---

## 📊 Яндекс.Метрика

Добавьте ваш счётчик в секцию:
```html
<script>
  ym(12345678, 'init', { clickmap:true, trackLinks:true });
</script>
```

---

## 🌐 GitHub Pages

Сайт уже доступен по адресу:  
🔗 https://alseptkg.github.io/flagship-landing/

Для публикации:
- Settings → Pages → Deploy from branch `main`, folder `/root`

---

## ⚙️ Возможности

- 📱 Адаптивный интерфейс
- 📦 Категории товаров с деталями
- ✅ Гарантия, возврат, логистика
- 🧩 Telegram-оповещения

---

© 2025 SEAL Group. Все права защищены.