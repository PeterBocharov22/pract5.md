### Задача 1
Исследование виртуальной стековой машины CPython.
Изучите возможности просмотра байткода ВМ CPython.

```bash
import dis

def foo(x):
    while x:
        x -= 1
    return x + 1

print(dis.dis(foo))
```
