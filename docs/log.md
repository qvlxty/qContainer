# Логи предыдущих версий

v 0.2

- **[MJ]** Полностью убран Sequelize по-умолчанию
- **[MJ]** Убран MysqlDbService
- **[MJ]** Используется по-умолчанию TypeORM
- **[MJ]** Добавлена функция init для инициализации контейнера
- **[MN]** Добавлены декораторы ControllerPrefix
- **[MN]** Рефактор генерируемой документации

v 0.1.1

- В ядро установлен сервис Passport
- Seed и дока по нему

v 0.1.0

- Гайд создания записной книжки
- Добавлены настройки для экземпляра приложения (модули)
- В ядро вынесен абстрактный класс для создания подключений к бд
- Контейнер теперь включает отдельное место для хранения подключения к бд
- Частью ядра стала реализация сервиса конфигурации.
- Каждый репозиторий автоматически обращается к созданному подключению к бд, поэтому регистрация БД Сервиса при наличии репозиториев обязательно
- Гибкая интеграция **middleware** в контроллеры
- Контейнер теперь может отдавать **список роутов**
- Жесткая привязка к **ejs + express**
- Автоматический модуль генерации спецификации API 
- Добавление модуля генерации API в ядро фреймворка
- Логи маунта/запуска/генерации/итд стали **цветными**

v 0.0.5

- В доку добавлены дополнительные данные о сервисах
- Изменена работа с контроллером

v 0.0.4 :

- Добавлен сервис для работы с Db подключениями
- Добавлена документация по моделям и репозиториям
- Модели заменены на репозитории

v 0.0.3 :

- Регистрация сервисов и моделей скрыта и автоматизирована
- Добавлены контроллеры и их модификация
- Фасад для создания приложений и его реализация для express
- Файл точки входа обновлен
- Методы для инсталляции роутов
- Настройка Api префикса для контроллеров

v 0.0.2 :

- Добавлено автоматическое создание сущностей, если их нет