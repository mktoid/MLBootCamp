# MLBootCamp

Задача "Прогноз отклика аудитории на интернет-опрос"

#86 из 214

https://mlbootcamp.ru/round/14/rating/

Есть результаты интернет-опроса. Известно, что часть аудитории прошла анкетирование полностью и корректно. Другая часть завершила опрос частично, с ошибками, или совсем отказалась от участия. Необходимо с максимально возможной точностью предсказать, кто из респондентов относится к первой группе, то есть прошел исследование полностью и без ошибок.

Основной файл с данными содержит 19 528 597 строчек (10Гб) и состоит из 6 столбцов:

1. cuid — идентификатор. Для одного идентификатора в файле может содержаться несколько записей;
2. cat_feature — некоторая категориальная переменная. Область значений: {0,1,2,3,4,5};
3-5. счетчики, собранные на основе поведения человека в интернете. Формат: {w_1: c_1, w_2: c_2, ...}, где w_i — это закодированный токен, а c_i — частота этого токена;
6. dt_diff — количество дней до даты, когда было получено значение целевой переменной.
Небольшой кусочек данных в качестве примера:

00000d2994b6df9239901389031acaac	5 {"809001":2,"848545":2,"565828":1,"490363":1} 
{"85789":1,"238490":1,"32285":1,"103987":1,"16507":2,"6477":1,"92797":2}	{}	39
