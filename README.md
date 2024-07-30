# ed-python-list-set-typle-dictionary

## Списки (Lists):

- Определение: Упорядоченные изменяемые коллекции элементов.
- Синтаксис: [1, 2, 3]
- Изменяемость: Изменяемые (можно добавлять, удалять или изменять элементы).
- Дублирование: Поддерживают дублирование элементов.

## Кортежи (Tuples):

- Определение: Упорядоченные неизменяемые коллекции элементов.
- Синтаксис: (1, 2, 3)
- Изменяемость: Неизменяемые (нельзя добавлять, удалять или изменять элементы).
- Дублирование: Поддерживают дублирование элементов.

## Множества (Sets):

- Определение: Неупорядоченные коллекции уникальных элементов.
- Синтаксис: {1, 2, 3} или set([1, 2, 3])
- Изменяемость: Изменяемые (можно добавлять или удалять элементы).
- Дублирование: Не поддерживают дублирование элементов.

## Словари (Dictionaries):

- Определение: Неупорядоченные коллекции пар "ключ-значение".
- Синтаксис: {"ключ1": "значение1", "ключ2": "значение2"}
- Изменяемость: Изменяемые (можно добавлять, удалять или изменять пары "ключ-значение").
- Дублирование: Ключи уникальны, значения могут дублироваться.

| |Синтаксис|Упорядоченность|Изменяемость|Дублирование|
|--------|--------|--------|--------|--------|
|List|[1,2,3]|✔️|✔️|✔️|
|Typle|(1,2,3)|✔️|✖️|✔️|
|Set|✖️|✔️|✖️|
|Dictionary|✖️|✔️|ключи - нет, значения - да|
