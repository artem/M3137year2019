# Конспекты М3237

![views per week](https://raw.githubusercontent.com/Jovvik/M3137year2019/traffic/traffic-M3137year2019/views_per_week.svg)

<!-- Если вы хотите помочь, всё, чего не хватает в конспектах - [тут](https://github.com/Jovvik/M3137year2019/issues/2) -->

Если нашли ошибку, пишите в [issues](https://github.com/Jovvik/M3137year2019/issues) или мне в телеграм @aeriu.

## 3 семестр

### Матанализ

#### Лекции

- [1 лекция](analysis/3sem/1.pdf)
- [2 лекция](analysis/3sem/2.pdf)
- [3 лекция](analysis/3sem/3.pdf)
- [4 лекция](analysis/3sem/4.pdf)
- [5 лекция](analysis/3sem/5.pdf)
- [6 лекция](analysis/3sem/6.pdf)
- [7 лекция](analysis/3sem/7.pdf)
- [8 лекция](analysis/3sem/8.pdf)
- [9 лекция](analysis/3sem/9.pdf)
- [10 лекция](analysis/3sem/10.pdf)
- [11 лекция](analysis/3sem/11.pdf)
- [12 лекция](analysis/3sem/12.pdf)
- [13 лекция](analysis/3sem/13.pdf)
- [14 лекция](analysis/3sem/14.pdf)
- [15 лекция](analysis/3sem/15.pdf)
- [Конспект к экзамену](analysis/3sem/final.pdf)

#### Практики 8-12
- [Конспект](analysis/3sem/practice.pdf)
- [Решения ДЗ](analysis/3sem/hw.pdf)
- [Краткий конспект](analysis/3sem/practice_short.pdf)

### Диффуры
- [1 лекция](diffeq/3sem/1.pdf)
- [2 лекция](diffeq/3sem/2.pdf)
- [3 лекция](diffeq/3sem/3.pdf)

- [Конспект к экзамену](diffeq/3sem/final.pdf)

## 2 семестр

### Матанализ
- [Итоговый конспект](analysis/2sem/final.pdf)

### Линейная алгебра
- [Итоговый конспект](linear%20algebra/2sem/final.pdf)

## 1 семестр

### Линейная алгебра
- [Конспект к экзамену](linear%20algebra/1sem/main.pdf) _(рендер pdf с векторами в github'e не работает, поэтому надо pdf скачивать)_

### Матанализ
- [Опрос #1](analysis/1sem/opros.pdf)
- [Опрос #2](analysis/1sem/opros2.pdf)
- [Конспект к экзамену](analysis/1sem/final.pdf)


## Как компилировать самому

Билд делается через `xelatex`, потому что я ~тупой и не понял сразу, как включить русский в нормальном латехе~ хотел адекватную поддержку русского. Но в `pdflatex` билдится, багов не замечал. Зависимостей тонны, так что проще сразу ставить самый полный набор пакетов, который можете, иначе будет боль с `tlmgr`.

Все, кроме конспектов лекций и первого опроса по матану, писалось с минимизацией копипаста через импорты кусков других файлов с помощью `catchfilebetweentags`, поэтому по отдельности ничего не компилируется.

В 1 семе первые пара лекций написаны в markdown, при этом из-за добавления тегов для импортов они теперь сломанные, но пдфки в оригинальном виде оставлены.
