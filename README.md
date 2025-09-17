Вот обновленный README.md с уменьшенными изображениями (в 2 раза меньше):

```markdown
# 📸 Collage Bot - Создание коллажей из фото и видео

![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)
![Telegram](https://img.shields.io/badge/Telegram-Bot-green.svg)
![Flask](https://img.shields.io/badge/Flask-2.0%2B-orange.svg)

## 📋 Описание проекта

**Collage Bot** - это Telegram-бот и веб-приложение, позволяющее создавать
профессиональные коллажи из фотографий и видео. Пользователи могут выбирать
различные сетки, размеры и легко создавать коллажи для социальных сетей.

## 🎯 Особенности

- ✅ Создание коллажей из фото и видео
- ✅ Выбор сетки (2x2, 1x3, 3x1, 1x3, 2x1, 1x2)
- ✅ Настраиваемые размеры (9:16, 3:4, 1:1, 4:3, 16:9)
- ✅ Поддержка подписки на канал
- ✅ Интерактивное создание коллажей в Telegram
- ✅ Скачивание готовых коллажей

## 🚀 Установка и запуск

### 1. Клонирование репозитория

```bash
git clone https://github.com/ваш_репозиторий/collage-bot.git
cd collage-bot
```

### 2. Установка зависимостей

```bash
pip install -r requirements.txt
```

### 3. Настройка переменных окружения

Создайте файл `.env` в корневой директории:

```env
TELEGRAM_BOT_TOKEN=ваш_токен_бота
CHANNEL_USERNAME=имя_канала
```

### 4. Запуск сервера

```bash
# Запуск Flask-сервера
python server.py

# Запуск Telegram-бота
python collageApp.py
```

## 📁 Структура проекта

```
collage-bot/
├── collage.html          # Веб-приложение для создания коллажей
├── collageApp.py         # Telegram-бот
├── server.py             # Сервер для создания коллажей
├── requirements.txt      # Зависимости
├── uploads/              # Папка для хранения временных файлов
├── .env                  # Конфигурация
└── README.md             # Документация
```

## 🤖 Использование бота

1. Начните диалог с ботом в Telegram
2. Подпишитесь на канал (обязательно для использования)
3. Выберите сетку для коллажа (2x2, 1x3, 3x1, 1x3, 2x1, 1x2)
4. Выберите размер коллажа
5. Загрузите фото и/или видео
6. Нажмите "Создать коллаж"
7. Скачайте готовый коллаж

## 🖼️ Примеры сеток

| Сетка | Описание |
|-------|----------|
| 2x2 | 2 строки, 2 столбца |
| 1x3 | 1 строки, 3 столбца |
| 3x1 | 3 столбца, 1 строка |
| 1x3 | 1 столбец, 3 строки |
| 2x1 | 2 столбца, 1 строка |
| 1x2 | 1 столбец, 2 строки |

## 📷 Примеры работы

<table>
  <tr>
    <td align="center">
      <strong>Диалог с ботом</strong><br>
      <img src="https://github.com/Ash-code-noCode/CollageBotApp/blob/main/photo_4_2025-09-17_19-45-12.jpg?raw=true" width="150">
    </td>
    <td align="center">
      <strong>Меню команд</strong><br>
      <img src="https://github.com/Ash-code-noCode/CollageBotApp/blob/main/photo_6_2025-09-17_19-45-12.jpg?raw=true" width="150">
    </td>
  </tr>
  <tr>
    <td align="center">
      <strong>Проверка подписки</strong><br>
      <img src="https://github.com/Ash-code-noCode/CollageBotApp/blob/main/photo_7_2025-09-17_19-45-12.jpg?raw=true" width="150">
    </td>
    <td align="center">
      <strong>Переход в мини-приложение</strong><br>
      <img src="https://github.com/Ash-code-noCode/CollageBotApp/blob/main/photo_2_2025-09-17_19-45-12.jpg?raw=true" width="150">
    </td>
  </tr>
  <tr>
    <td align="center" colspan="2">
      <strong>Готовый коллаж</strong><br>
      <img src="https://github.com/Ash-code-noCode/CollageBotApp/blob/main/photo_2025-09-17_19-56-12.jpg?raw=true" width="300">
    </td>
  </tr>
</table>

## 🔧 Требования

- Python 3.8+
- Telegram Bot API Token
- Ссылка на Telegram-канал для подписки
- Установленные зависимости из `requirements.txt`

## 🛠️ Зависимости

```txt
Flask==2.3.3
python-telegram-bot==13.15
moviepy==1.0.3
requests==2.31.0
Pillow==10.0.1
numpy==1.24.3
opencv-python==4.8.1.78
```


## 📬 Поддержка

По вопросам и предложениям обращайтесь к разработчику через GitHub Issues.

---

*Создано с ❤️ для любителей творчества и социальных сетей*
```
