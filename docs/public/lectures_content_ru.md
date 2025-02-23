# Краткий конспект лекций

## Лекция 1. Установочная встреча.

Знакомство с преподавателем. Общая структура курса. Формирование итоговой оценки. Основные идеи, закладываемые в
курс. Место курса в образовательной программе.

## Лекция 2. Знакомство с Python. Преимущества и недостатки.

Историческая справка: история релизов, автор языка, причины бурного роста популярности. 
Основные ниши. Сильные стороны языка, его основной недостаток.
Существующие подходы к ускорению программ на Python. Как выполняется программа на Python.
Байт-код, машинный код. Компиляция и интерпретация.
Интерпретируемость как один из источников замедления работы по сравнению с 
компилируемыми языками. Механика присваивания с точки зрения памяти. Переменные как имена.
Автоматический сбор мусора как один из источников замедления работы программы.

## Лекция 3. Числа и условия.

Числа как неизменяемые типы данных. Встроенные типы для работы с числами: `int`, `float`, `complex`.
Способы создания чисел: литералы, экспоненциальная форма, вызов конструктора. 
Приведение типов: явное и неявное. Арифметические операции:
связь с типами, сокращённые версии. Вспомогательные функции: `abs`, `pow`, `round`. Условия: базовый синтаксис,
объединение условий, форматирование цепочек условий, таблица истинности. Расширение условной конструкции через
`elif` и `else`.

## Лекция 4. Строки как неизменяемые последовательности.

Тернарный оператор как однострочная версия условной конструкции `if/else`. Проверки `==` и `is`. 
Рекомендации по проверке типа объекта. Отличия в проверке на истинность и на явное соответствие `True`.
Строки как неизменяемые последовательности. Способы создания строк. Мотивация различного набора кавычек при 
создании строковых констант. Экранирование как трюк для работы со специальными символами. Неизменяемость строк.
Ограниченная поддержка арифметических операторов. Свойства последовательностей: индексируемость, возможность взятия
срезов, итерируемость, поддержка оператора `in/not in`, длина, поддержка функций `min` и `max`, `count`, `index`. 
Итерирование по строкам: по элементам, по индексам с помощью функции `range`, по индексам и элементам одновременно
с помощью `enumerate`. Основные строковые методы: `lower`, `strip`, `find`, `replace`. Вызов строковых методов 
через оператор `.`.

## Лекция 5. Форматирование строк. Списки как изменяемые последовательности.

Строки: методы `split`, `join`. Форматирование строк с помощью `f-строк`. Списки как изменяемые последовательности.
Демонстрация изменяемости через добавление, удаление и обновление. Различные способы добавления новых элементов:
`append`, `extend` и `insert`. Различные способы удаления элементов: `remove`, `pop` и `del`.
Ловушка разделяемых ссылок. Виды копирования: поверхностное и глубокое. Срезы как способ поверхностного копирования 
последовательностей. Модуль `copy` и его основные функции: `copy` и `deepcopy`.

## Лекция 6. Кортежи. Словари.

Генераторы списков. Кортежи как неизменяемые последовательности. Особенности создания кортежей: состоящие из 
одного элемента, перечисление без скобок. Неизменяемость кортежей. Мотивация для использования кортежей: фиксированные
структуры, скорость работы, сохранность данных. Словари как неупорядоченные изменяемые коллекции с доступом по ключу.
Способы создания словарей. Изменяемость словарей: добавление, удаление, изменение существующих ключей. 
Требования к ключам словаря. Проверка наличия ключа в словаре. Итерирование по словарям.

## Лекция 7. Функции.

Объявление функции с помощью  `def`. Требования и рекомендации к именованию функций. 
Аргументы функции: позиционные и именованные.
Опциональные подсказки типов в описании аргументов и возвращаемых значений. Вызов функции и её объявление.
Возврат результатов функции с помощью `return`. Возврат и обработка нескольких значений. Сопоставление
аргументов при вызове функции: позиционное и по имени. Произвольное количество аргументов функции при 
помощи `*args` и `**kwargs`.

## Лекция 8. Введение в классы.

Сложность программного обеспечения как основной мотивирующий фактор для развития парадигм программирования.
Связь данных и действий в рамках процедурного программирования и объектно-ориентированного
программирования. Объект, класс или шаблон, экземпляр класса. 
Классы как пользовательские типы. Синтаксис создания классов. 
Магический (или служебный) метод `__init__` - инициализатор класса. Понятие `self` - ссылка на текущий
экземпляр.
