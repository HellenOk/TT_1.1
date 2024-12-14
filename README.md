# TT_1.1 
Расчеты произведены в Power BI, результаты вставлены в формы в EXCEL.

### Task1
На вкладке call log отображена работа операторов. Указаны оператор, игрок, которому звонили.
В поле Call логируется попытка звонка. Если ячейка пустая, звонка не было, 0 - недозвон, 1 - дозвон
На вкладке Activity показана активность игроков - игрок, дата активности, тип активности, сумма. Считаем что вся активность была после событий на call log.
Требуется свести статистику в разрезе каждого оператора, сколько звонков было сделано, сколько было успешных дозвонов.
Так же, сколько уникальных игроков совершало депозиты после дозвона от оператора и сумма депозитов после дозвона.
Депозиты на вкладке activity в колонке Type, фильтр по значению Deposit.

![image](https://github.com/user-attachments/assets/805c3b71-e7cf-4c46-a5a3-4c3b8a1c5f3f)

### Task2
Делаем допущения, что сейчас пятница 28.07.2017.
На вкладке activity2 есть список активностей игроков. С понедельника по четверг. Дата, сумма, тип активности.
В пятницу планируется отправить оповещения игрокам, которые вносили депозиты в течении недели. Игрокам будут предлодены бонусы, которые зависят от того, сколько 
человек заплатил за прошедшие дни. На вкладке Bonus расписано при какой сумме какой бонус.
Необходимо составить список уникальных игроков с пометкой, сколько активных дней он играл за прошедшие дни (активный день - день, в котором был депозит, в одном 
активном дне у игрока может быть неограниченное количество депозитов), а так же номером бонуса, который ему будет предложен.

![image](https://github.com/user-attachments/assets/81602e75-ada0-4744-a91e-bfe20942fcba)


