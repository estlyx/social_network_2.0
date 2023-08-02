# Social network #

__Необходимо спроектировать и разработать Django-сервис друзей__

Сервис должен предоставлять возможности:
* Зарегистрировать нового пользователя
* Отправить одному пользователю заявку в друзья другому
* Принять/отклонить одному пользователю заявку в друзья от другого
* Посмотреть пользователю список своих входящих и исходящих заявок в друзья
* Посмотреть пользователю список своих друзей
* Получить пользователю статус дружбы с каким-то другим пользователем
* Удалить пользователю другого пользователя из своих друзей

___
### Пример запуска и использования API находится в `Issues`
___
Приложение `users` управляет пользователяии и заявками в друзья, т.е. всем, что требуется от проекта

URLS для `users`:
1. `login`: Страница входа в аккаунт
2. `logout`: Страница выхода из аккаунта
3. `register`: Страница регистрации
4. `search_users`: Страница поиска друзей
5. `my_profile`: Страница своего профиля
6. `edit_profile`: Страница редактирования своего профиля
7. `friends`: Страница друзей пользователя

У всех страниц наверху есть панель навигации, которая позволяет легко переходить между ними

## Запуск приложения:
```
git clone https://github.com/estlyx/social_network_2.0.git
cd social_network
pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
```
Перейдите по адресу http://localhost:8000
