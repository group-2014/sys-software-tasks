## Перечень тем для самостоятельной работы по дисциплине "Системное программное обеспечение"

### Как пользоваться этим файлом

Если вы выбрали тему, необходимо отредактировать файл, добавив в скобках после темы свои фамилии (не более двух), а также ссылку на репозиторий, в котором вы будете выполнять работу. Если тема уже была выбрана кем-то ранее — не страшно, можно сделать форк и доработать код. Проверять такие работы буду гораздо внимательнее, но если увижу, что вы действительно усовершенствовали чужой код (исправили, добавили новые фичи, убрали старые бага, провели рефакторинг и т.д.), и он от этого стал лучше, хорошая оценка вам гарантирована.
* Не стоит устраивать "войн правок", когда уже выбранная кем-то тема потом переходит к кому-то другому. Мы работаем в системе версионного контроля, т.е. все изменения будут видны в истории коммитов.
* Спам не допускается, нарушители будут забанены.
* Если вы придумали свою тему, допишите её в конец списка (фамилии исполнителей и ссылка на репозиторий также обязательны).
* Этот файл можно править либо напрямую, т.к. вы все являетесь членами этой группы и у вас есть права на запись в этот репозиторий, а также можно сделать форк у себя в аккаунте, а затем пул-реквест сюда. Последнее даже интереснее :grimacing:.
 
### Список тем
№|Тема|Ссылка на описание|Имя
:---:|---|:---:|:---:
1|Реализация кодов Рида—Соломона.|[Восстановление данных](https://goo.gl/rZQZzU)|Кравчук
2|Реализация алгоритма циклического избыточного кода.|[Проверка целостности данных](https://goo.gl/OUUfGf)|
3|Реализация кодов Боуза—Чоудхури—Окенгема.|[Восстановление данных](https://goo.gl/uA2WOc)|
4|Реализация алгоритма Шеннона—Фано.|[Сжатие данных]( https://goo.gl/Ty119S)|Борботько
5|Реализация алгоритма Лемпеля—Зива—Велча.|[Сжатие данных](https://goo.gl/DGqP9E)|Генько
6|Реализация алгоритма быстрого умножения больших целых чисел Шёнхаге—Штрассена.|[описание](https://goo.gl/ni2BFp)|
7|Реализация алгоритма быстрого умножения больших целых чисел Фюрера.|[описание](https://goo.gl/Us3fyT)|
8|Реализация алгоритма быстрого деления больших целых чисел Бурникеля—Циглера.|[описание](https://goo.gl/2QmFXg)|
9|Реализация алгоритма Ривеста—Шамира—Адлемана.|[Криптография. Шифрование](https://goo.gl/z3eO8o)|
10|Реализация алгоритма Кнута—Морриса—Пратта.|[Поиск подстроки в строке](https://goo.gl/S4RDMu)|
11|Реализация алгоритма Бойера—Мура.|[Поиск подстроки в строке](https://goo.gl/ZFLesC)|Лабчук
12|Реализация алгоритма поиска по «радужным таблицам».|[Криптография. Дешифровка хэшей](https://goo.gl/E9uJce)|
13|Реализация приложения под Android (любое, лишь бы интересное).| |
14|Реализация приложения под iOS (любое, лишь бы интересное).| |
15|Реализация библиотеки определения языка текста.| |
16|Реализация простейшей игры с применением библиотеки PyGame.|[PyGame](http://pygame.org/)|Зименко
17|Реализация простейшей игры с применением библиотеки Cocos2d-x.|[Cocos2d-x](http://www.cocos2d-x.org/)|
18|Реализация алгоритма детектирования ошибок Дамма.|[описание](http://goo.gl/A2KeQJ)|
19|Реализация алгоритма поиска контрольной суммы.|[Adler-32.](https://goo.gl/lp8450)|
20|Реализация алгоритма поиска контрольной суммы Флетчера.|[описание](https://goo.gl/3uewT8) (english)|
21|Реализация алгоритма Боейра—Ватсона для случая триангуляции Делоне.|[Траингуляция](https://goo.gl/uQMWYS)|
22|Реализация алгоритма Гилберта—Джонсона—Кёрти.|[min расстояние между выпуклыми множествами](https://goo.gl/bTs7Yy)|
23|Информер погоды.||[Плешков](https://github.com/mz15/weather_informer)
24|Переводчик.||[Гашков](http://bit.ly/1Xravum)
### Требования к программе

**Программы, написанные не на Си оцениваются в индивидуальном порядке.**

1. Соблюдение соблюдение единого стиля кодирования.
2. Использования стандартной библиотеки Си.
3. Модульность (несколько файлов с исходным кодом, заголовочные файлы).
4. Создание собственных функций.
5. Оригинальность идеи (если тема не из списка или язык не Си).
6. Наличие коммитов и брэнчей.
7. Наличие wiki-страницы с документаций и описанием программы или алгоритма (это не должна быть копипаста Википедии).
8. Наличие файла README.md с коротким описанием программы (что делает, как запустить и т.д.).
9. Кроссплатформенность — программа должна работать хотя бы под Виндоус и Линукс.
10. Использование структур, перечислений и объединений; свои собственные типы через алиасы.
11. Использование массивов, динамическое распределение памяти приветствуется, но не обязательно.
12. Использование указателей (обязательно!).
13. Работа со строками (в Си это весело!).
14. Наличие понятного текстового интерфейса (можно и графического, можно на ncirses).
15. Программа должна вести лог-файл и адекватно реагировать на нештатные ситуации. Как минимум нужно отображение того, что произошло непосредственно перед падением программы.
16. Умение отвечать на вопросы по своей программе и объяснять, как работает тот или иной участок кода по моему выбору.

По каждому пункту вы можете получить 8 баллов, итого 16×8=128 баллов за программу.
