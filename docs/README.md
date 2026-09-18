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