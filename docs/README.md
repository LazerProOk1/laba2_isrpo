# Geometric Lib

## Краткое описание
Описание библиотеки geometric_lib на Python для вычисление площадей и периметров геометрических фигур

## Функции

### circle.py

**area(r)** — площадь круга
```python
>>> area(5)
78.53981633974483
```

**perimeter(r)** — длина окружности
```python
>>> perimeter(5)
31.41592653589793
```

### square.py

**area(a)** — площадь квадрата
```python
>>> area(4)
16
```

**perimeter(a)** — периметр квадрата
```python
>>> perimeter(4)
16
```

### rectangle.py

**area(a, b)** — площадь прямоугольника
```python
>>> area(4, 5)
20
```

**perimeter(a, b)** — периметр прямоугольника
```python
>>> perimeter(4, 5)
18
```

### triangle.py

**area(a, b, c)** — площадь треугольника по формуле Герона
```python
>>> area(3, 4, 5)
6.0
```

**perimeter(a, b, c)** — периметр треугольника
```python
>>> perimeter(3, 4, 5)
12
```


## История изменений
| Хеш | Сообщение |
|---|---|
| 8ba9aeb | L-03: Circle and square added |
| d078c8d | L-03: Docs added |
| 104b56c | Add rectangle.py with area and perimeter formulas |
| 00ace11 | Add triangle.py with area and perimeter formulas and fix rectangle perimeter formula |
| f7e9f96 | fix formulas in triangle.py |
| c40a725 | add .gitignore |
| 95444de | add documentation |
| 29c1c23 | add comments into python files |