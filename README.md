
# Архитектура ПО. Семинар 09. Способы организации передачи данных между компонентами приложения, протоколы и API. REST, gRPC, очереди

Разработать полную ERD домена, по UML-диаграмме из урока

## Компонентная UML-модель приложения для аренды облачных ресурсов

![Компонентная UML-модель приложения для аренды облачных ресурсов](/Seminar09-page01.png "UML-модель")

## ERD домена приложения для аренды облачных ресурсов
![ERD домена приложения для аренды облачных ресурсов](/Seminar09-page02.png "ERD домена")

### Краткое описание доменной модели

1. Таблица Orders: номер заказа, дата заказа, идентификатор пользователя, идентификатор VDS, количество оплаченных месяцев, время истечения срока аренды;
2. Таблица User: имя пользователя, телефон, email, количество средств на счету;
3. Таблица VDS_spec: идентификатор OS, CPU, RAM, Disk, IP-адреса, итоговую стоимость аренды;
4. Таблица OS: семейство ОС, версия ОС, цена;
5. Таблица RAM: объем оперативной памяти (ГБ), цена;
6. Таблица IP: тип IP-адреса, количество адресов, итоговая стоимость пула адресов;
7. Таблица CPU: название процессора, число ядер, рабочая частота, цена;
8. Таблица Disk: тип диска, его емкость(ГБ), цена.