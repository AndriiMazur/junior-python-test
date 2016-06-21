написать сервис, который бы по интервалу дат возвращал статистику по часам:
* количество всего заказов за час
* количество успешных заказов за час (статус = `SUCCESS`)
* количество уникальных райдеров за час
* количество уникальных драйверов за час
* среднее количество заказов за последние 7 часов
* отношение количества заказов за час к количеству заказов в тот же час предыдущего дня

в качестве источника данных использовать `fake-orders.csv`

Предполагается использование Flask и Pandas
