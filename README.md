# Курсовой UrbanProjectFlask

Проект в рамках обучения в Urban University.  
Используемая версия Python 3.12

## Установка

Следуйте этим инструкциям для установки проекта на локальную машину для разработки и тестирования.
1. Клонируйте репозиторий:
    ```bash
    git clone https://github.com/ZehrBit/UrbanProject-Flask.git
    cd UrbanProject-Flask
    ```
2. Создайте и активируйте виртуальное окружение:  
    Команда для создания:
    ```bash
    python -m venv venv
    ```
    Активация на Linux:
    ```bash
    source venv/bin/activate
    ```
    Активация на Windows
    ```bash
    .venv\Scripts\activate
    ```
4. Установите зависимости:
    ```bash
    pip install -r requirements.txt
    ```
5. Создайте базу данных и выполните миграции:  
    Инициализируйте систему миграций:
    ```bash
    python manage.py migrate
    ```
    Создайте миграцию:
    ```bash
    flask db migrate -m "Initial migration."
    ```
    Примените миграцию:
    ```bash
    flask db upgrade
    ```

## Запуск на локальном компьютере
1. Запустите сервер разработки:
```bash
python app.py
```

2. Перейдите по адресу в вашем браузере, чтобы увидеть работающий проект.
```bash
http://127.0.0.1:5000
```

## Контакты
Email: zehrbit@gmail.com  
Telegram: https://t.me/zehrbit
