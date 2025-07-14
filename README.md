# TinderBolt ⚡🤖❤️

[![Java](https://img.shields.io/badge/Java-17%2B-blue)](https://java.com)
[![Telegram Bot](https://img.shields.io/badge/Telegram%20Bot-API-brightgreen)](https://core.telegram.org/bots/api)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Release](https://img.shields.io/github/release/AlexH73/TinderBolt.svg)](https://github.com/AlexH73/TinderBolt/releases)


TinderBolt - интеллектуальный Telegram-бот для знакомств, который использует ChatGPT для генерации:
- Привлекающих внимание открывающих сообщений 🎯
- Виртуальных свиданий со знаменитостями 🌟
- Индивидуальных ответов для повышения шансов на успех 💬

![Пример работы бота](src/main/resources/images/main.jpg)

## ✨ Возможности
- **Генератор открывающих сообщений**: Создаёт уникальные сообщения для начала диалога
- **Режим виртуального свидания**: Общайся с "знаменитостями" как в реальном чате
- **Персонализированные ответы**: Адаптирует сообщения под стиль общения
- **Готовые сценарии**: Встроенные шаблоны для разных ситуаций знакомств
- **Интерактивное меню**: Удобная навигация по кнопкам

## 🚀 Как запустить
1. Клонируйте репозиторий:
```bash
git clone https://github.com/AlexH73/TinderBolt.git

```

2. Установите зависимости:
```bash
mvn clean install
```

3. Настройте переменные окружения:
```env
BOT_NAME=YourBotName
BOT_TOKEN=your_telegram_bot_token
OPENAI_API_KEY=your_openai_api_key
```

4. Запустите приложение:
```bash
mvn exec:java -Dexec.mainClass="com.javarush.telegram.TinderBoltApp"
```
## 🚀 Быстрый старт
1. Создайте бота в [@BotFather](https://t.me/BotFather)
2. Получите API-ключ на [OpenAI](https://platform.openai.com/)
3. Клонируйте репозиторий:

```bash
git clone https://github.com/AlexH73/TinderBolt.git
```
4. Запустите бота:
```bash
mvn exec:java -Dexec.mainClass="com.javarush.telegram.TinderBoltApp"
```
## ⚙️ Технологии
- Java 17
- Telegram Bot API
- OpenAI ChatGPT API
- Maven
- Lombok

## 📂 Структура проекта
```
src/
├── main/
│   ├── java/
│   │   └── com/javarush/telegram/
│   │       ├── TinderBoltApp.java          # Главный класс
│   │       ├── MultiSessionTelegramBot.java # Обработчик Telegram
│   │       ├── ChatGPTService.java         # Интеграция с OpenAI
│   │       ├── UserInfo.java               # Модель пользователя
│   │       └── DialogMode.java             # Режимы диалога
│   └── resources/
│       ├── images/                         # Медиа-контент
│       ├── messages/                       # Тексты сообщений
│       └── prompts/                        # Шаблоны для ChatGPT
```

## 🤝 Как внести вклад
1. Форкните репозиторий
2. Создайте новую ветку (`git checkout -b feature/amazing-feature`)
3. Сделайте коммит изменений (`git commit -m 'Add some amazing feature'`)
4. Запушьте ветку (`git push origin feature/amazing-feature`)
5. Откройте Pull Request

## 📜 Лицензия
Этот проект распространяется под лицензией [MIT](LICENSE).

---
> Создано с ❤️ для упрощения знакомств в цифровую эпоху
