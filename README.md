# Описание предметной области
*Перервозка грузов* — это транспортировка товаров автомобильным, железнодорожным и т.д. транспортом между поставщиками и крупными торговыми точками, фабриками или складами


## Сущности предметной области
1. Товар
2. Заказчик
3. Поставщик
4. Транспорт
5. Перевозчик
6. Оплата
7. Логист
8. Маршрут
9. Пункт погрузки
10. Пункт выгрузки



## Отношения между сущностями

1. **Заказчик**-*Договариается о приобретении товара*->**Поставщик**.
2. **Товар**-*Приобретается с помощью*->**Оплата**.
3. **Товар**-*Осуществляет перевозку через*->**Перевозчик**.
4. **Логист**-*составляет*->**Маршрут**.
5. **Товар**-*загружается*->**Пункт погрузки**.
6. **Товар**-*осуществяет транспортировку в*->**Транспорт**.
7. **Перевозчик**-*осуществляет движение по*->**Маршрут**.
8. **Товар**-*выгружается*->**Пункт выгрузки**.





# Описание проекта

Проект разрабатывается как **справочник** по принципу работы структуры перевозок.<br>
Он позволит узнать отношение **товара** и **перевозок**. Даст представление о внутренем строении логики перевозки грузов


# Этапы развития проекта

- [x] Добавить описание
- [x] Выделить все сущности и отношения между ними
- [ ] Описать поведение связанное с сущностями
- [ ] Описать процессы предметной области
 
