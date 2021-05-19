# tree_func
Implements the tree function for bash

### Задача

Вывести все директории и файлы по заданному пути. В конце на новой строке вывести количество директорий и файлов.

#### Входные данные

Едининственный аргумент скрипта - путь в виде (путь может отличаться от представленного примера:

```bash
bash script.bash .
```

#### Выходные данные

В стандартный вывод вывести структуру в виде

```bash
.
├── abc
├── aberdeen
│   ├── aa
│   │   ├── aa
│   │   │   └── aaa.txt
│   │   ├── aaa
│   │   │   ├── ability
│   │   │   │   ├── abc
│   │   │   │   ├── abilities
│   │   │   │   │   ├── aa.txt
│   │   │   │   │   └── ab
│   │   │   │   │       └── abandoned.pdf
│   │   │   │   ├── ability
│   │   │   │   │   └── aberdeen
│   │   │   │   └── ab.txt
│   │   │   └── ab.pdf
│   │   └── aaa.doc
│   ├── aa.jpg
│   └── ab
│       └── aa.jpeg
└── abilities
    └── aaa.txt

10 directories, 12 files
```
