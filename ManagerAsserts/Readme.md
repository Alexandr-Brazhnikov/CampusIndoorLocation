# Сервис управления оборудованием

Ответственность: создание, изменение,просмотр и удаление записи об оборудовании

## Пользовательские истории

Как Организатор я хочу изменить время/место/оборудование _моего_ мероприятия

Как Персонал я хочу знать где/когда/кто проводится мероприятия, использующие оборудование

Как Руководитель я добавляю новое оборудование
 
Как Руководитель я оцениваю загруженность оборудования по времени 

## Модель данных
ERD диаграмма
![3](https://user-images.githubusercontent.com/73663755/163939504-2811ad5e-5f64-44b2-afd6-2f9b07c897b4.jpg)


Диаграмма классов
![diagr](https://user-images.githubusercontent.com/73663755/163938651-088f032d-394e-483b-858d-81ed210b78e6.jpeg)

## API сервиса
/api/managerasserts — список всех оборудований

/api/managerasserts/{assertId} — конкретное оборудование

/api/managerassert/add — добавление оборудования

/api/delete — очистить список оборудований

/api/delete/{assertId} - удалить конкретное оборудование

