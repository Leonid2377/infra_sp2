# infra_sp2
#Описание проекта
Проект позволяет зарегистрироваться пользователям
и оставлять отзывы на различные произведения

**Как пользоватся**:
>Скопировать проект командой: 
>> `git clone`

>Установить и активировать виртуальное окружение
>>`python3 -m venv env`
> 
>>`source env/bin/activate`
> 
>>`python3 -m pip install --upgrade pip`
 
>Установить зависимости:
>> `pip install -r api_yamdb/requirements.txt`


>Запустить из директории infra:
>> `docker-compose up -d --build`
>
>>`docker-compose exec web python manage.py migrate`

> остановить проект: `docker-compose down -v`

**Автор проекта: Старостин Леонид** 
