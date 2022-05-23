## Образа 1С:Предприятие

ВАЖНО: В данных репозитариях нет бинарных файлов дистрибутивов, а только инструменты для скачивания их с сайта и сборки в образы. Для их использования вам в любом случае придется использовать учетную запись к сайту https://users.v8.1c.ru/ и обладающую доступом к скачиванию соответствующих дистрибутивов

### Сборка образов проверена на версиях:

```
8.3.16.1659
8.3.17.1851
8.3.18.1363
8.3.18.1483
8.3.21.1302
```

-  ### [Onec-base](https://github.com/TheDemonCat/onec-base) [![Build onec base](https://github.com/TheDemonCat/onec-base/actions/workflows/docker-image.yml/badge.svg)](https://github.com/TheDemonCat/onec-base/actions/workflows/docker-image.yml)

    Базовый образ. Предназначен для дальнейшей установки платформы. В нем устанавливаются все зависимости, согласно документации. 

- ### [Onec-full](https://github.com/TheDemonCat/onec-full) [![Build onec full](https://github.com/TheDemonCat/onec-full/actions/workflows/blank.yml/badge.svg)](https://github.com/TheDemonCat/onec-full/actions/workflows/blank.yml)
    
     Образ с установленными всеми компонентами платформы 1С:Предприятие. Основывается на onec-base.
    Реализована поддержка версии платформы 8.3.20 и выше

- ###  [Onec-server](https://github.com/TheDemonCat/onec-server.git) [![Build onec server](https://github.com/TheDemonCat/onec-server/actions/workflows/ci.yaml/badge.svg)](https://github.com/TheDemonCat/onec-server/actions/workflows/ci.yaml)

    Образ с установленным и запущенным сервером 1С:Предприятие. Основывается на onec-base.
    Реализована поддержка версии платформы 8.3.20 и выше

- ### [Onec-client](https://github.com/TheDemonCat/onec-client.git) [![Build onec client](https://github.com/TheDemonCat/onec-client/actions/workflows/ci.yaml/badge.svg)](https://github.com/TheDemonCat/onec-client/actions/workflows/ci.yaml)

    Образ с установленным клиентом сервером 1С:Предприятие и графическим сервером.
       Реализована поддержка версии платформы 8.3.20 и выше

- ### [onec-edt](https://github.com/TheDemonCat/onec-edt.git)
    
   WIP: Образ с сервером 1С:Предприятие и EDT. Основывается на onec-base.

- ### [Onec-instance](https://github.com/TheDemonCat/onec-instance) 

    Docker-compose - запуск сервера 1С Предприятия на базе OS Linux. Работоспособность образа была проверена на Ubuntu 18. При развертывании требуется права администратора, для записи в файл /etc/hosts. Так же была проверена работоспособность образа на Windows10, но с обязательным использованием [WSL2](https://docs.microsoft.com/ru-ru/windows/wsl/wsl2-install)

## Скачивание дистрибутивов с https://users.v8.1c.ru/

- [Oneget](https://github.com/v8platform/oneget) [![Build oneget](https://github.com/v8platform/oneget/actions/workflows/releaser.yaml/badge.svg)](https://github.com/v8platform/oneget/actions/workflows/releaser.yaml) - Приложение для скачивания релизов с users.1c.v8.ru. 

## Прочие образа

[Traefi2](https://github.com/TheDemonCat/traefik2-compose) - docker-compose - запуск Edge Router. Предназначен для быстрой публикации контейнеров и назначении DNS имен. Подробнее [тут](https://docs.traefik.io/)
