# Quadratic Equations Solver

Вычисляет корни квадратного уровнения

# Как использовать

Пример (в python скрипте):
```python
from quadratic_equation.py import get_roots


a = float(input('a: '))
b = float(input('b: '))
c = float(input('c: '))

root1, root2 = get_roots(a, b, c)

print("x1={}\nx2={}".format(root1, root2))
```

# Как тестировать

```bash
$ python tests.py  # может понадобиться вызов python3 вместо python,
# зависит от настроек операционной системы
```

# Как настроить тест автоматически

Скопируете файл hooks/pre-commit в .git/hooks и измените его так, чтобы
все пути (shell, python и тестовый скрипт) соответствлвали файлам в
вашей системе.

После этого при коммите будет запускаться тест и коммит прервётся, если
тест не будет пройден

# Цель проекта

Код написан в целях обучения.

[DEVMAN.org](https://devman.org)
