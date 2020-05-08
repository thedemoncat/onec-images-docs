## Образа 1С:Предприятие

ВАЖНО: В данных репозитариях нет бинарных файлов дистрибутивов, а только инструменты для скачивания их с сайта и сборки в образы. Для их использования вам в любом случае придется использовать учетную запись к сайту https://users.v8.1c.ru/ и обладающую доступом к скачиванию соответствующих дистрибутивов


- [onec-base](https://github.com/TheDemonCat/onec-base) - Базовый образ. Предназначен для дальнейшей установки платформы. В нем установливаются все зависимости, согласно документации

- [Onec-full](https://github.com/TheDemonCat/onec-full) - Образ с установленными всеми компанентами платформы 1С:Предприятие. Основывается на onec-base.

- [onec-server]() - TODO

- [onec-instance](https://github.com/TheDemonCat/onec-instance) - Docker-compose - запуск сервера 1С Предприятия на базе OS Linux. Работоспособность образа была проверена на Ubuntu 18. При развертывании требуется админские права, для записи в файл /etc/hosts. Так же была проверена работоспособность образа на Windows10, но с обязательным использованием [WSL2](https://docs.microsoft.com/ru-ru/windows/wsl/wsl2-install)

## Скачивание дистрибутивов с https://users.v8.1c.ru/

- [downloader](https://github.com/TheDemonCat/onec_downloader) - Скрипт скачивания релизов с users.1c.v8.ru. Основан на [этом](https://github.com/Infactum/onec_dock/blob/master/download.sh) скрипте. Так же часть идей позаимствованна от [сюда](https://github.com/jugatsu/onec-docker/blob/master/scripts/download.sh) 

## Прочие образа

[traefi2](https://github.com/TheDemonCat/traefik2-compose) - docker-compose - запуск Edge Router. Предназначен для быстрой публикации контейнеров и назначении DNS имен. Подробнее [тут](https://docs.traefik.io/)