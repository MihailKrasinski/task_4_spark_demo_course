<h1 align="center">Questions for interview</h1>


## Description

Здесь будут вопросы, которые могу вам попасться на собесе.

 
## Questions

1) Что такое Spark
2) Из первого вопроса вытекает что такое Map Reduce и в чём его суть 
3) Какие этапы есть в Map Reduce
4) Разница между Spark и Hadoop
5) RDD, DF, Dataset - разнциа между ними(в рамках PySpark только RDD и DF)
6) Что такое DAG и как это связано со спарком
7) Разница между действиями и трансформациями
8) Разница между узкими и широкими трансформациями
9) Что такое job, stage, task
10) Виды джойнов(не лефт, райт и иннер, а именно стратегий джойна в спарке)
11) Когда какой джойн юзать
11) Почему нельзя писать бездумно collect и прочие такие штуки
12) Разница между repartion и coalesce(просто ответа что coalesce ток уменьшает а repartition может и увеличивать мало, мало даже если человек скажет что repartition это 
shuffle всегда). Логику того как под капотом это работает. Плюсы и минусы
13) как работает partitionBy
14) PartitionBy в комбинации с repartition или coalesce
15) Как уменьшить количество shuffle
16) Оптимизации которые юзает каталист
17) Как решить проблему Data Skew и вообще что это такое
18) UDF и почему PySpark UDF это плохо. Чем заменить PySpark UDF
19) Delta Lake и почему он
20) Менеджмент памяти на уровне JVM+overhead
21) Менеджмент памяти на полном уровне(если это PySpark то там не ток JVM и overhead)
22) Parquet - что это(рассказать всё что знаешь)
23) Нюансы при чтении JSON
24) Нюансы при чтении CSV
25) Broadcast variables

## Answers

https://github.com/egorkapot/spark_innowise/tree/main/Questions_for_interview
