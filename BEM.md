# БЭМ

**Статус:** черновик.

## Именование классов

Для обозначения БЭМ-сущностей зачастую используется специальный формат строки, по которой можно однозначно определить, какая именно сущность представлена.

В оригинальном стиле такая строка будет выглядить следующим образом:
```
block[_blockModName[_blockModVal]][__elemName[_elemModName[_elemModVal]]]
```
(В квадратных скобках необязательные параметры)

- `block-name` — блок.
- `block-name_mod-name_mod-val` — модификатор блока в формате ключ-значение.
- `block-name_mod` — булевый модификатор блока.
- `block-name__elem-name` — элемент блока.
- `block-name__elem-name_mod-name_mod-val` — модификатор элемента в формате ключ-значение.
- `block-name__elem_mod` — булевый модификатор элемента.
