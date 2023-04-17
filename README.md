[Урок 1. Введение в тестирование ПО](#урок-1-введение-в-тестирование-по)

[Урок 2. Работа с документацией](#урок-2-работа-с-документацией)

[ Урок 3.Создание чек листов](#урок-3создание-чек-листов)

[Урок 4.Создание тест-кейсов](#урок-4создание-тест-кейсов)

[Урок 5.Создание баг-репортов. Баг-трекинговые системы](#урок-5создание-баг-репортов-баг-трекинговые-системы)
____
# Урок 1. Введение в тестирование ПО

## Что будет на уроке?

[1. Что такое тестирование?](#1что-такое-тестирование)

[2. Что такое качество?](#2качество)

[3. Цели тестирования и роль тестировщика](#3цели-тестирования-и-роль-тестировщика)


[4. Принципы тестирования](#4-принципы-тестирования)

[5. Тестовая среда и тестовые данные](#5-тестовая-среда-и-тестовые-данные)

[6. Testing, QS, QA](#6-testing-qc-qa)

# 1.Что такое тестирование?

### ISTQB
*International Software Testing Qualifications Board*
* Международный совет по тестированию программного обеспечения;
* Цель - стандартизировать знания и умения тестировщиков.

Тестирование - это *проверка* чего угодно проведением _*тестов*_, то есть зарание подготовленного списка вопросов, проверок или испытаний.

-----

# Тестирование програмного обеспечения

Проверка соответсвия реального поведения программы ожидаемому.

## Задачи:
 1. определить, что они сооветствуют описанным требованиям;
 2. показать, что они подходят для заявленных целей
 3. найти дефекты
 ------

 ## Общие признаки тестирования
 -----
 1. Продукт с неизвестными показателями
 2. Список проверок
 3. Правила поведения исследования
 4. Ожидаемый результат
 5. Фактический результат
------

## Тестирование по ISQTB
___

### Насколько ПО качественное?
* Поэтапный процесс- включает в себя несколько областей, мы не подходим к тестированию хаотично тут всё довольно структурированно. тестовая документация - чек-листы, тест-кейсы, баг репорты.Любое действие тестировщика прописано и их нужно выполнять одно за другим.

* Включает статистические и динамические активности. Статическое тестирование - это тестирование без запуска самой программы т.е. это тестирование требований, макетов, тестовых данных - это какое-то конфигурирование тестового окружения( так же сюда входит написание чек-листов и тест-кейсов и другой тестовой документации). Динамическое тестирование - это когда продукт уже разработан отдан в тестирование, мы этот продукт запускаем и начинаем тестировать его.
* Выявляет соответствие и отклониение от них ( дефекты) т.е. баг репорты- если ожидаемый результат отличается от получаемого - мы нашли баг и заводим на него баг репорт.

___

# 2.Качество

Цель тестирования это дать оценку качества программного обеспечения.

Качество - это степень, в которой какой- то компонент, система или процесс отвечает требованиям и ожиданиям пользователя и заказчика. 

# Критерии качества

## 1. Функциональность

Степень, где продукт выполняет задачи для которых создан:
* функциональная полнота; 
* Функциональная правильность;
* функциональная целесообразность;

> пример - Задачи сигнализации
>* информировать пользователя;
>* взаимодействовать с автомобилем;
_____

## 2. Эффективность

Производительность продукта
или системы:
* поведение в зависимости от времени;
* использование ресурсов;
* вместимость.

>Например, как быстро обрабатываются
запросы пользователей с мобильного
приложения сигнализации

____

# 3.Надежность

Способность быстро восстанавливать
работу при отказе оборудования:

* завершенность;
* доступность;
* отказоустойчивость;
* восстанавливаемость.

>Например, когда сел аккумулятор,
вы его заменили и телеметрическое
оборудование перезапустилось
____

# 4.Удобство использования

Насколько эффективно продукт
удовлетворяет потребности пользователя:

* узнаваемость;
* обучаемость;
* работоспособность;
* защита пользователя от ошибок;
* эстетика пользовательского
интерфейса;
* доступность.


>Пользователь понимает куда он должен
попасть, когда нажимает на ту или иную
кнопку.
____

# 5.Поддерживаемость

Степень адаптируемости приложения
к изменениям:

*  модульность;
*  повторное использование;
*  пригодность к анализу;
*  модифицируемость;
*  тестируемость.

> Например, как быстро пользователь найдет нужный ему товар, анализ- с каких браузеров заходит пользователь
____

# 6.Переносимость

Легкость переноса
из одного программного
или аппаратного окружения в другое:
* адаптивность;
* простота и легкость установки;
* заменяемость.

>Например, мы захотели перенести наш сайт на новую платформу,

____

# 7.Безопасность

Степень защиты информации и данных:
* конфиденциальность;
* целостность;
* ответственность;
* подлинность.
>Например, пользовательские данные не должны никуда утекать все данные должны быть шифрованые и не должны быть доступны третьим лицам.

___

# 8.Совместимость


Степень, в которой продукт обменивается
информацией с другими продуктами
или системами:
* сосуществование;
* совместимость.
>Например, в нашем маркет плейсе мы делаем новую систему оплаты и наш маркетплейс должен нормально передавтаь данные в эту систему.


# 3.Цели тестирования и роль тестировщика.

## Цели тестирования

* Оценить рабочие продукты на соответствие
стандартам компании.
* Проверить, все ли требования выполняются.
* Обнаружить отказы и дефекты.
* Снизить уровень риска ненадлежащего качества программного
обеспечения, например, пропущенные
сбои в работе.
* Обеспечить соблюдение договорных, правовых
или нормативных требований (стандартов).
___

# 6. Testing, QC, QA

# Обязанности инженера QA

1. Составление ТЗ на устранение найденных после
тестирования недочетов; т.е. баг репортов
2. Мониторинг и отслеживание правок;(проверить что баг действительно исправен)

3. Проведение повторных тестов на отсутствие найденных ошибок; 

4. Анализ и оптимизация этапов разработки для устранения причин ошибок и избежания повторного их появления;(например тестеровщики нашли какой-то баг,разработчики его исправили- после этого на этот баг нужно написать тест кейс что бы в будущем мы могли этот баг обнаружить )

5. Работа с тестовой документацией.(написание чек листов баг репортов каких то отчетов)

6. Изучение и уточнение требований к программному
обеспечению у заказчика;
7. Написание и последующая доработка сценариев
тестирования;
8. Проведение тестирования функционала ПО;
9. Составление отчетов по обнаруженным недочетам
в трекинговую систему;
10. Анализ результатов и показателей проведенных тестов.

# 4. Принципы тестирования

## 7 принципов тестирования: 

1. Тестирование демонстрирует наличие дефектов.(всегда есть какие то дефекты и баги)

2. Исчерпывающее тестирование недостижимо.(невозможно поверить продукт полностью покрыть тестами)

3. Раннее тестирование.(нужно приступать к тестированию настолько рано насколько это возможно)

4. Скопление дефектов.(нужно приступать к тестированию той части функционала где как мы думаем наибольшие скопление багов и ошибок)

5. Парадокс пестицида.(нужно понимать что написаные нами тест кейсы со временем перестают вылавливать ошибки)

6. Тестирование зависит от контекста.(например есть несколько пользователей у них разные роли и проверять их нужно по разному)

7. Заблуждение об отсутствии ошибок.( ошибки и баги есть всегда просто мы их еще не нашли)


____
# 5. Тестовая среда и тестовые данные.

## Тестовые среды

1. Локальное окружение(окружение которое находится на нашем компьютере)
2. Тестовое окружение(где-то развернутое окружение для тестирования специальный тестовый стенд)
3. Staging-окружение(окружение в которое мы выкатываем весь наш протестированный функционал)
4. Боевое окружение(непосредственно рабочая версия для всех пользователей)

___
# Тестовые данные

Набор входных значений, требуемых для выполнения
тестов.
Тестировщики создают тестовые данные вручную
или с применением инструментов генерации:

* таблицы Excel;
* онлайн-утилиты;
* скрипты для выполнения в командной строке;
* сложные программы, созданные самими тестировщиками.
___

# Testing, Quality Control, Quality Assurance.

* QC — Контроль качества продукта —
анализ результатов тестирования
и качества новых версий выпускаемого
продукта.

* QA — Обеспечение качества продукта
— изучение возможностей
по изменению и улучшению процесса
разработки, улучшению коммуникаций
в команде, где тестирование является
только одним из аспектов обеспечения
качества.
* Тестирование — это уже
непосредственно процесс проверки
результатов работы на соответствие
установленным требованиям.

*Hard-skils* -это обычно технические навыки

*Soft-skils* - это  обычно личностные качества

<kbd><img src="https://github.com/TatyanaProtas/QA-GEEK-BRAINS/blob/main/Lesson1pic1.png?raw=true" />  
</kbd>

<kbd><img src="https://github.com/TatyanaProtas/QA-GEEK-BRAINS/blob/main/Lesson1pic2.png?raw=true" />  
</kbd>

# Урок 2. Работа с документацией
## Что будет на уроке

[1. Что такое техническое задание](#что-такое-техническое-задание)

[2. Как работать с техническим заданием](#как-работать-с-техническим-заданием)

[3. Кем составляются технические задания](#кем-составляются-технические-задания)

# Что такое техническое задание

*Техническое задание* — описание функций и условий, которые выполняет приложение в процессе решения задачи. Это отправная точка процесса разработки.


* Постановка задачи разработчику
* Определяют функции, которые должно выполнять приложение или его часть
___

<kbd><img src="https://github.com/TatyanaProtas/QA-GEEK-BRAINS/blob/main/Lesson2pic1.png?raw=true"/></kbd>

## Функциональные требования
Что должна делать программа?
* Определяют стандарты производительности зопасности, масштабируемости и др
* Помогают разработчикам определять технические возможности и ограничения системы
___

## Нефункциональные требования

Как должна работать программа?

* Определяют стандарты производительности,
безопасности, масштабируемости и др
* Помогают разработчикам определять технические возможности и ограничения системы

___
# Как работать с техническим заданием 
__Тестировщик__ участвует в проверке и анализе требований, находит неясности
и противоречия, предоставляет отзыв о функциях и удобстве использования
будущего приложения.
___

# Атрибуты требований

* Полнота - есть вся необходимая информация
* Однозначность - у каждого требования недвусмысленные формулировка
* Непротиворечивость - требования не противоречат друг другу и сами себе
* Модифицируемость - в требование можно внести изменение
* Осуществимость - требование должно быть физически реализуемым
* Проверяемость - должна быть возможность проверки реализации требования



<kbd><img src="https://github.com/TatyanaProtas/QA-GEEK-BRAINS/blob/main/Lesson2pic2.png?raw=true "/></kbd>


___

## Баг на требования

Пример

Название. Требование No1 — неполное
Описание. В требовании непонятно, как именно себя ведет система, если дата не указана - поле "Возраст" будет пустым или будет скрыто из анкеты?
___

# Кем составляются технические задания

Кто составляет требования?
* продакт-менеджер или бизнес-аналитик
* заказчик
* технический писатель
_____

# Урок 3.Создание чек листов

## Создание чек-листов. Теория

Что будет на уроке

[1. Что такое чек-лист](#1-что-такое-чек-лист)

[2. Составление чек-листов](#2-составление-чек-листов)

[3. Тестирование по чек-листам](#3-тестирование-по-чек-листам)

[4. Резолюция](#4-резолюция)

[5. Где составлять и хранить чек-листы](#5-где-составлять-и-хранить-чек-листы)
_____


# 1. Что такое чек-лист

## Чек-лист
Чек-лист – это список, содержащий ряд проверок во время тестирования программного продукта.

Овощи и фрукты:
* апельсины
* бананы
* морковь

Колбасный отдел:
* ливерная колбаса

Молочный отдел:
* йогурт
* молоко
* сливки

Соки и воды:

* яблочный сок
* боржоми


# 2. Составление чек-листов

Составление чек-листов

1. Изучить рецепт пирога
2. Составить чек-лист последовательности приготовления блюда
3. Во время приготовления отмечать выполненные пункты чек-листа
4. После прохождения по всем 

a. пунктам чек-листа делается

b. вывод о готовности блюда
___
## Последовательность действий
1. Сначала изучить техническое задание
2. Сгруппировать проверки в разделы
3. Определить тестовые данные
4. Приступить к составлению тестовой документации 
В каких программах составляется: Excel, Checkvist,
TestRail, TestIT, Qase.io…

Насколько детальным будет чек-лист зависит от требований,
уровня знания продукта сотрудниками и сложности продукта.
___
## Правила составления чек-листа
1. Один пункт – одна операция
2. Пункты всегда начинаются с существительного или глагола неопределенной формы
3. Соблюдать структуру
4. Опираться на требования
5. Давать пунктам чек-листа названия по форме, общей для всех членов команды
<kbd><img src="путь к изображению" /></kbd>
# 3. Тестирование по чек-листам
# 4. Резолюция
# 5. Где составлять и хранить чек-листы


# Урок 4.Создание тест-кейсов

# Урок 5.Создание баг-репортов. Баг-трекинговые системы
<kbd><img src="путь к изображению" /></kbd>