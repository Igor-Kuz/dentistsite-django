# Dental clinic website where you can book visit to your doctor

Site allows to send email via gmail

Инструменты разработки Стек:

Python >= 3.7 
Django >= 3.1
sqlite3


Разработка

1)Клонировать репозиторий через git clone 
2)Создать виртуальное окружение python -m venv venv
3)Активировать виртуальное окружение
4)Устанавливить зависимости: pip install -r reqirements.txt
5)Настройка Gmail
# Email Settings
# myaccount.google.com/lesssecureapps
# accounts.google.com/DisplayUnlockCaptcha
# myaccount.google.com/apppasswords
EMAIL_HOST = 'smtp.gmail.com'
EMAIL_PORT = 587
EMAIL_HOST_USER = 'youraccount6@gmail.com'
EMAIL_HOST_PASSWORD = ''
EMAIL_USE_TLS = True
5)Запустить сервер python manage.py runserver
