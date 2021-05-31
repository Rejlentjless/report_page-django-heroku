## V2 - Report page

### Использовалось:
- Django
- немного Bootstrap
- Deploy на Heroku

> ### Тестовое задание
> 
> Вам необходимо создать проект Django, который должен соответствовать следующим требованиям
> - Анонимный пользователь может получить доступ только к странице README и формам входа или регистрации.
> - Пользователь может создавать, удалять или просматривать список только своих записей.
> - Чтобы создать запись, пользователь предоставит следующие данные:
> ○ дата
> ○ расстояние
> ○ продолжительность
> - Когда пользователь видит список записей, приложение также показывает среднюю скорость.
> - Пользователь должен иметь возможность фильтровать список записей по диапазону дат.
> - Должна быть страница с недельной статистикой за последний год - номер недели, общее количество записей, общее расстояние, общая продолжительность и средняя скорость за неделю.
> - Требуется минимальный внешний вид. Вы можете использовать несколько бесплатных шаблонов, также вы должны использовать некоторую структуру макета для внешнего интерфейса, например, bootstrap. Вы можете использовать цветовую схему по умолчанию. Но ответ приложения не должен быть простым текстом, добавлять (прикреплять) верхний и нижний колонтитулы, таблицы и списки, когда это необходимо.

> Это минимальная задача, которую ставит перед приложением. Если у вас есть больше времени и вы хотите проявить больше навыков, вы можете выполнять бонусные задания. Они не являются обязательными, и вы можете выбрать любые из них в другом порядке.
> Бонусные задания
> - Подготовьте конфигурацию settings.py для использования в различных средах (например, локальный, сервер разработки, сервер продукта). Разумные данные, такие как пароли, секреты, ключи API, не должны передаваться в git.
> - Добавьте управляющие аккаунты. Разрешения должны работать так:
> ○ Пользователь - может управлять только собственными записями.
> ○ Менеджер - может создавать пользователей, активировать и деактивировать их или сбрасывать пароль пользователя. Но менеджер не может получить доступ к пользовательским данным.
> ○ Администратор - может управлять пользователями в качестве менеджеров, а также может просматривать данные всех пользователей и создавать записи от имени другого пользователя.
> - Покрытие модульных тестов.
> - Предоставьте инструкции по развертыванию и настройку.
> - Интегрируйте вход через социальные сети (Facebook, Google, любой другой поставщик OAuth по вашему выбору).
> - Выполняйте задачу как отдельные серверные и внешние приложения. Бэкэнд должен предоставлять REST или RPC API.
> ○ Никогда не перезагружайте интерфейсную страницу, даже для аутентификации.
> - Управляющая команда (или другая фоновая задача, например, сельдерей) для отправки пользователю его ежегодного
 