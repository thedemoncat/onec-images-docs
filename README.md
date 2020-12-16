## Образа 1С:Предприятие

ВАЖНО: В данных репозитариях нет бинарных файлов дистрибутивов, а только инструменты для скачивания их с сайта и сборки в образы. Для их использования вам в любом случае придется использовать учетную запись к сайту https://users.v8.1c.ru/ и обладающую доступом к скачиванию соответствующих дистрибутивов


- [Onec-base](https://github.com/TheDemonCat/onec-base) - Базовый образ. Предназначен для дальнейшей установки платформы. В нем устанавливаются все зависимости, согласно документации

- [Onec-full](https://github.com/TheDemonCat/onec-full) - Образ с установленными всеми компонентами платформы 1С:Предприятие. Основывается на onec-base.

- [Onec-server](https://github.com/TheDemonCat/onec-server.git) - Образ с установленным и запущенным сервером 1С:Предприятие. Основывается на onec-base.

- [Onec-client](https://github.com/TheDemonCat/onec-full.git) - Образ с установленным клиентом сервером 1С:Предприятие и графическим сервером. Основывается на onec-full.

- [onec-edt](https://github.com/TheDemonCat/onec-edt.git) - Образ с сервером 1С:Предприятие и EDT. Основывается на onec-base.

- [Onec-instance](https://github.com/TheDemonCat/onec-instance) - Docker-compose - запуск сервера 1С Предприятия на базе OS Linux. Работоспособность образа была проверена на Ubuntu 18. При развертывании требуется права администратора, для записи в файл /etc/hosts. Так же была проверена работоспособность образа на Windows10, но с обязательным использованием [WSL2](https://docs.microsoft.com/ru-ru/windows/wsl/wsl2-install)

## Скачивание дистрибутивов с https://users.v8.1c.ru/

- [Downloader](https://github.com/TheDemonCat/onec_downloader) - Скрипт скачивания релизов с users.1c.v8.ru. Основан на [этом](https://github.com/Infactum/onec_dock/blob/master/download.sh) скрипте. Так же часть идей позаимствованна от [сюда](https://github.com/jugatsu/onec-docker/blob/master/scripts/download.sh) 

## Прочие образа

[Traefi2](https://github.com/TheDemonCat/traefik2-compose) - docker-compose - запуск Edge Router. Предназначен для быстрой публикации контейнеров и назначении DNS имен. Подробнее [тут](https://docs.traefik.io/)
