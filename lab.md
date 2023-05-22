# Межсетевой экран с зональной политикой 
## Часть 1: Базовая конфигурация устройства
### Настройте имена хостов, IP-адреса интерфейсов и пароли доступа на маршрутизаторах.
### Настройте статические маршруты, чтобы обеспечить сквозное подключение на маршрутизаторах.
### Настройте порты доступа и магистрали на коммутаторе.
## Часть 2: Настройка брандмауэра политики на основе зон (ZPF)
### Используйте интерфейс командной строки для настройки брандмауэра политики на основе зон.
### Используйте интерфейс командной строки для проверки конфигурации.
## Часть 3: Проверка функциональности брандмауэра ZPF

## Часть 1. Проведем базовую настройку сети по заданию
### ![](https://github.com/igorvrn/otus5/blob/main/002.png)
### Но сетевые устройства в CPT знают не все команды, в связи с чем собираем данную конфигурацию в EVE-NG.
### ![](https://github.com/igorvrn/otus5/blob/main/019.png)
## Проведем первоначальную настройку оборудования в соответствии с заданием и проверим сетевую связанность с помощью команды ping:
### ![](https://github.com/igorvrn/otus5/blob/main/003.png)
### ![](https://github.com/igorvrn/otus5/blob/main/004.png)
## Часть 2. Создадим и настроим зоны безопасности на R3 в соответствии с заданием: 
### ![](https://github.com/igorvrn/otus5/blob/main/005.png)
### ![](https://github.com/igorvrn/otus5/blob/main/006.png)
### ![](https://github.com/igorvrn/otus5/blob/main/007.png)
### ![](https://github.com/igorvrn/otus5/blob/main/008.png)
## Проверим работу настройку  зон безопасности:
### ![](https://github.com/igorvrn/otus5/blob/main/010.png)
### ![](https://github.com/igorvrn/otus5/blob/main/011.png)
### ![](https://github.com/igorvrn/otus5/blob/main/012.png)
### ![](https://github.com/igorvrn/otus5/blob/main/013.png)
## Проверим работу настройку  зон безопасности:
### Чтобы получить дополнительную информацию о парах зон, их картах политик, картах классов и счетчиках совпадений, используем команду show policy-map type inspect zone-pair command:
### ![](https://github.com/igorvrn/otus5/blob/main/014.png)
### Часть 3. Проверим работу ZPF для пинга между зонами безопасности.
### ![](https://github.com/igorvrn/otus5/blob/main/015.png)
### ![](https://github.com/igorvrn/otus5/blob/main/016.png)
### ![](https://github.com/igorvrn/otus5/blob/main/017.png)
