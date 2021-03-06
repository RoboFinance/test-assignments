# Robofinance php developer test assignment

Тестовое задание для php-разработчика в компанию [Robofinance](http://robo.finance).

## Task

Создать приложение, которое имеет следующие возможности: 
1. Планирование отложенного перевода средств со счёта текущего пользователя на счёт выбранного пользователя. Требования к функционалу:
    * Пользователь указывает сумму перевода в рублях, дату и время перевода (с точностью до часа).
    * Сумма перевода ограничена балансом клиента на момент планирования перевода.
    * Способ выбора пользователя - любой (можно просто ввод ID).
    * Ввод данных должен валидироваться как на стороне клиента, так и на стороне сервера с выводом ошибок пользователю.
2. Реализация процесса выполнения запланированных переводов. Здесь не допускается ситуация, при которой у какого-либо пользователя окажется отрицательный баланс.
3. Отображение на сайте списка всех пользователей и информации об их одном последнем переводе. 

### Code quality

* Решение должно быть выполнено с использованием одного из современных PHP фреймворков.
* Написанный для решения задачи код не должен содержать уязвимостей. 
* Код `php` должен соответствовать стандартам [PSR](https://www.php-fig.org/psr/psr-12/).
* Процесс регистрации и проверки прав доступа можно не реализовывать. 
* Внешний вид страниц значения не имеет.
* Приветствуется соблюдение различых принципов современной разработки.

Решение задачи должно содержать:
1. Ссылку на тэг с версией тестового задания (расположено на [github](https://github.com/RoboFinance/test-assignments)) в `readme.md`.
2. Четкую инструкцию по развертыванию проекта с целью проверки его работоспособности. Приветствуется использование Docker.
3. Миграции и тестовые данные для наполнения БД.
4. Тесты.

Решение можно прислать ссылкой на хранилище исходного кода ([GitHub](https://github.com/), [Bitbucket](https://bitbucket.org/) и др.).