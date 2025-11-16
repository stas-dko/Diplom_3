## Дипломный проект. Задание 3: веб-приложение
Тестирование веб-приложения Stellar Burgers https://stellarburgers.education-services.ru/

1. Восстановление пароля
2. Личный кабинет 
3. Проверка основного функционала
4. Раздел «Лента заказов»

# Запуск автотестов

* Установите зависимости
``` shell
pip3 install -r requirements.txt
```
* Запустить все тесты из директории tests
```shell
pytest tests --alluredir=allure_results
```
* Посмотреть отчет в веб версии пройденного прогона
``` shell
allure serve allure_results
```# Diplom_2
