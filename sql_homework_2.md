# SQL#2

## 1.Вывести водителей со ставкой меньше 50 и их автомобили с пробегом меньше 80000

```sql
select *
from driver d
left join car c on d.id_driver = c.id_driver
where d.rate < 50 and c.odo < 80000
```

## 2.Вывести водителей с автомобилями в порядке размера платы, от большего к меньшему и их автомобили, отсортированные от меньшего пробега к большему

```sql
select d.first_name, c.model, d.rate, c.odo
from driver d
join car c on d.id_driver = c.id_driver
order by d.rate desc, c.odo
```

## 3.Вывести всех водителей и их автомобили, если они есть

```sql
select d.first_name, c.model
from driver d
left outer join car c on d.id_driver = c.id_driver
```

## 4.Вывести все автомобили и их водителей, если они есть

```sql
select d.first_name, c.model
from car c
left outer join driver d on d.id_driver = c.id_driver
```

## 5.Вывести автомобили у которых нет водителей

```sql
select c.*
from car c
where c.id_driver is null
```
