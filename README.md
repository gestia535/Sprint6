# Sprint6
Проект по автоматизации UI-тестов для сервиса «Яндекс Самокат»
Описание проекта
Этот проект направлен на автоматизацию UI-тестов (Firefox браузер) для веб-приложения «Яндекс Самокат», предназначенного
для аренды самокатов.

Структура репозитория
В корневой директории проекта вы найдете следующие файлы и папки:

pages: содержит классы для каждой тестируемой страницы.
tests.py: включает файлы с тестами для различных страниц приложения.
locators: файлы с определениями локаторов, используемых в тестах.
conftest.py: содержит фикстуры, необходимые для выполнения тестов.
test_data: файлы с тестовыми данными.
allure_results: JSON-файлы с результатами выполнения тестов для генерации отчетов.
requirements.txt: список всех внешних зависимостей, необходимых для выполнения тестов.
README.md: руководство по проекту.

Покрытие тестами

test_home_page: проверка корректности отображения текста ответов в разделе «Вопросы о важном» на главной странице, 
а также проверка переходов на главную страницу сервиса и на главную страницу «Дзена» при клике по логотипу.

test_order_form_page: проверка процесса оформления заказа через позитивный сценарий с использованием двух наборов данных
и из разных точек входа для начала оформления заказа.

Запуск всех тестов

Для установки зависимостей выполните: pip install -r requirements.txt
Чтобы запустить все тесты, используйте команду: pytest -v

Генерация отчета о тестировании: allure serve allure_results

