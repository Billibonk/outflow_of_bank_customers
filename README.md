# Описание проекта.
Из банка стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых.
Необходимо:
- спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Вам предоставлены исторические данные о поведении клиентов и расторжении договоров с банком;
- построить модель с предельно большим значением F1-меры.

Обучение с учителем. Работа с несбалансированными данными.

# Задача проекта 
Анализ оттока клиентов из банка для выбор стратегии (удержание старых клиентов или привлечение новых клиентов).

# Описание данных

## Признаки

RowNumber — индекс строки в данных

CustomerId — уникальный идентификатор клиента

Surname — фамилия

CreditScore — кредитный рейтинг

Geography — страна проживания

Gender — пол

Age — возраст

Tenure — сколько лет человек является клиентом банка

Balance — баланс на счёте

NumOfProducts — количество продуктов банка, используемых клиентом

HasCrCard — наличие кредитной карты

IsActiveMember — активность клиента

EstimatedSalary — предполагаемая зарплата

## Целевой признак

Exited — факт ухода клиента

# Вывод

1. Спрогнозирована вероятность ухода клиента из банка в ближайшее время.
2. Построена модель с предельно большим значением F1-меры с последующей проверкой на тестовой выборке. Доведена метрика до 0.605. 
