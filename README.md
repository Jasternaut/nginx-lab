# Лабораторная работа №1: Nginx + Docker

## 👩‍💻 Автор
ФИО: Патрушев Руслан Андреевич
Группа: ИП2

---

## 📌 Описание задания
Создать веб-сервер в Docker с использованием Nginx и подключить HTML-страницу.  
Результат доступен по адресу [http://localhost:8080](http://localhost:8080).

---

## ⚙️ Как запустить проект

1. Клонировать репозиторий:
   ```bash
   git clone https://github.com/Jasternaut/nginx-lab
   cd nginx-lab
Запустить контейнеры:
```bash
docker-compose up -d --build
```
Открыть в браузере:
```http://localhost:8080```
📂 Содержимое проекта

```docker-compose.yml``` — описание сервиса Nginx

```code/index.html``` — главная HTML-страница

```screenshots/``` — все скриншоты

📸 Скриншоты работы

<img width="500" src="screenshots/about_success.png"></img>
<img width="500" src="screenshots/docker_success.png"></img>
<img width="500" src="screenshots/html_success.png"></img>
<img width="500" src="screenshots/html_success_2.png"></img>
<img width="500" src="screenshots/port_success.png"></img>
<img width="500" src="screenshots/version_success.png"></img>

✅ Результат
Сервер в Docker успешно запущен, Nginx отдаёт мою HTML-страницу.
