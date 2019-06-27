# SQL homework

## 1.Вывести всех водителей с фамилиями в алфавитном порядке

```sql
select d.*
from driver d
order by d.last_name
```

## 2.Вывести всех водителей в порядке размера платы, от большего к меньшему

```sql
select d.*
from driver d
order by d.rate desc
```

## 3.Вывести автомобили отсортированные от меньшего пробега к большему

```sql
select c.*
from car c
where c.odo
order by c.odo
```

## 4.Вывести водителей со ставкой больше 30

```sql
select d.*
from driver d
where d.rate > 30;
```

## 5.Вывести автомобили с пробегом больше 100000

```sql
select c.*
from car c
where c.odo > 100000
```

## 6.Вывести самую большую ставку у водителей

```sql
select max(d.rate)
from driver d
```

## 7.Вывести самую маленькую ставку у водителей

```sql
select min(d.rate)
from driver d
```

## 8.Вывести самый большой пробег автомобиля

```sql
select max(c.odo)
from car c
```
