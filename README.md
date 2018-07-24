

<img src="img/green.png" width="50" height="50">

# Cpp-lab-2

## Задачи для практикума №2 (шаблоны функций)

### Задача №1


> Написать шаблонную функцию `msort`, сортирующую массив элементов `T` слиянием. Если тип элемента массива `char*`, то производится сортировка по длине строк.

Результатом решения задачи должен стать заголовочный файл `task1.h` и основной файл программы `main1.cpp` с демонстрацией работы шаблонной функции.

### Задача №2


> Написать шаблонную функцию `createArr`, создающую динамический массив элементов типа `T` размером `N`. Каждый элемент массива возвращается внешней шаблонной функцией `gen`, указатель на которую принимает функция `createArr`.
> 

Результатом решения задачи должен стать заголовочный файл `task2.h` и основной файл программы `main2.cpp` с демонстрацией работы шаблонной функции.

### Задача №3


> Написать шаблонную функцию `map`, принимающую по ссылке массив элементов типа `T` и выполняющую преобразование каждого элемента в соответетствии с шаблонной функцией `change`, указатель на которую передается в `map`.

Результатом решения задачи должен стать заголовочный файл `task3.h` и основной файл программы `main3.cpp` с демонстрацией работы шаблонной функции.
 
 
 
## Список участников/веток

|  ФИО              | Имя ветки |
|-------------------|-----------|
| Алексеева В.     | b1 |
| Белов А.     | b2 |
| Булатова М.    | b3 |
| Зобов М.|  b4 |
| Зубова М.         | b5  |
| Исхаков М.        | b6 |
| Косолапов В.       | b7 |
| Котрикова К.     | b8 |
| Коченко А.       | b9 |
| Макаров Д.     | b10 |
| Михайлова И.           | b11 |
| Орлова Т.   | b12  |
| Парьев Д.      | b13 |
| Першина А.        | b14 |
| Решетников Н.            | b15 |
| Семенов А. | b16 |
| Серов Д.      | b17 |
| Смирнова М. | b18 |
| Сорокин А.  | b19 |
| Тимофеев С.   | b20 |
| Тюлькин А.     | b21 |
| Федяков М.   |  b22 |
| Яковлев Д.   | b23 |

## Алгоритм выполнения работы

Для выполнения работы необходимо:

1. Выполнить *fork* репозитария в свой аккаунт.
1. Выполнить клонирование репозитария из своего аккаунта к себе на локальную машину (`git clone`).
1. Создать ветку **git** с индивидуальным номером (`git branch имя_ветки`).
1. Сделать ветку активной (`git checkout имя`).
1. Необходимо разместить как исходные файлы с решениями задач, поместив **cpp** файлы в **src**, а заголовочные - в **include**. 
1. Добавить файлы в хранилище (`git add`).
1. Выполнить фиксацию изменений (`git commit -m "комментарий"`).
1. Отправить содержимое ветки в свой удаленный репозитарий (`git push origin имя_ветки`).
1. Создать пул-запрос в репозитарий группы и ждать результата от **Travis-CI**.

