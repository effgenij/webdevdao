## RoR: таск-менеджер с функцией аутентификации

**Функции приложения**

Полный процесс авторизации пользователя:

- Регистрация нового пользователя, Sign in, Sign out, Forgot Password, Unlock, Update Account. 

- После регистрации пользователь попадает на список задач, которые либо он создал сам, либо ему назначили. 

- Создать полный CRUD процесс задач: создание, удаление, просмотр, изменение.

**Требования к реализации**

У пользователя есть следующие атрибуты:

- имя, фамилия — обязательные поля;

- email — обязательное поле, уникальное;

- пароль;

У задачи следующие атрибуты:

- название задачи — обязательно;

- описание задачи — текст, не обязательно;

- кто создал — пользователь, обязательно;

- на кого назначена — пользователь, обязательно;

- статус задачи — new, started, finished.

Требования к вьюшкам:

- HAML или Slim;

- Twitter Bootstrap;

- JQuery.

Требование к коду:

- Rspec - тестовое покрытие кода 100 %, проверка через гем Simplecov (вьюшки тестировать не надо);

- зелёный Rubocop.

**Оценка задания**

При оценке тестового задания будут учитываться следующие пункты:

- следование Style Guides;

- соответствие требованиям к тестированию, полнота тестов;

- DRY;

- наличие «интересной функции», которая не описана в требованиях, но может быть полезной в проекте.

Код выложить на GitHub или Bitbucket и прислать ссылку.