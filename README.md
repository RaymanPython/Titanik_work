

# Titanik_work
https://youtu.be/tjOJ-SEvmGA видео презентация
Использовал 
Jupyter Notebook 
Язык: python
Библиотеки: pandas

Количество лиц мужского пола 577.
Количество лиц женского пола 314.
Среди пассажиров больше мужчин чем женщин.
60 процентов от всех пассажиров составляют взрослые мужчины.
В первом классе: 216 человек
Во втором классе 2: 184 человек
В третьем классе 3: 491 человек

выводы которые можно сделать из таблицы describe:

минимальный возраст 0.42 года,
максимальный возраст 80 лет,

средний возраст 29.699118 лет,

пассажиры Титаника были достаточно молодыми.

У 177 человек неизвестен возраст.

Создаём новую таблица survived_ratings в которой будут только выжившие 
Пассажиры


количество выживших мужчин: 109
количество выживших женщин: 233
процент взрослых выживших мужчин 25.730994152046783

Процент выживших взрослых мужчин значительно меньше чем процент взрослых мужчин изначально

Замен пустых ячеек, их всего: 869
Общее количество пустых клеток среди выживших пассажиров: 262
общее количество пустых клеток среди выживших пассажиров: 262
общее количество пустых клеток среди выживших пассажиров: 262
Пустые клетки есть в столбцах с названиями: age, embarked, deck, embark_town

Пропуски
На самом деле, удаление пропусков — это грубое решение проблемы неполных данных, потому что после удаления у нас останется не так много данных, как хотелось бы, а нам нужно получить из них полезные выводы.
Неизвестные значения в стоблце age я заменю на среднее значение что бы не сильно поменять среднее значение возраста и максимальный и минимальный возраст
в столбце embarked замени пустые клетки на значение котрое больше всего появляется в этом столбце S, 

в столбце deck заменим на значение котрое больше всего появляется в этом столбце nan 
embark_town пустые клетки заменем на S

Спасибо за внимание!
