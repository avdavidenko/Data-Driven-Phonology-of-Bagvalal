# Фонология багвалинского языка: от словарных данных к обобщениям
## (курсовая работа студентки 3 курса Фундаментальной и прикладной лингвистики А.В. Давиденко)


## Работа программы
Программа получает на вход словарь багвалинского языка в виде текстового файл в формате HTML. На выходе программа создает таблицы с данными в формате CSV. Программа написана в среде Jupyter Notebook, поэтому для открытия кода необходимо использовать эту среду.

## Считывание и подготовка данных
Программа считывает текстовый файл построчно. Каждая строка - словарная статья для одного слова или разных вариантов одного слова. Из строки выбираются данные о лемме, окончании, диалекте и переводе слова. Для дальнейшего анализа каждая лемма переводится в IPA.

## Анализ данных
В ходе работы программа выделяет инициали, финали и интервокальные кластеры каждого слова. Для обработки данных использована библиотека pandas.
