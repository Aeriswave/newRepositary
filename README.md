## Описание формата разработки и поддержки решений  
Назначение: подготовка к проекту (пресейл), проектная работа, разработка решений и проектной документации, внедрение, эксплуатация  
### 1. Папки репозитария:  
>**./BOOK** Для проектной и эксплутационной документации, книг, описаний  
>**./TOOL** Инструментарий  
>**./GOLD** Условия и результат оплаты  

### 2. Этапы разработки и поддержки в деревьях GIT (GIT branches)  
#### (1) Основные ветви (branches) для разделения на этапы:  
>**1PRE** = подготовка к разработке, сбор исходных данных, систематизация, анализ, формирование требований и подготовительной документации  
>**2DEV** = развитие (разработка), создание прототипа, разработка нового функционала  
>**2RED** = правки, модификации, изменения, оптимизация существующего функционала  
>**2TST** = тестирование прототипа, функционала, изменений, совместимости  
>**3RUN** = тестовая эксплуатации  
>**4SUP** = осуществляется техподдержка (фиксация, диагностика и решение проблем в стабильной версии)
>**4BUG** = исправление небольших ошибок  
>**4RAT** = исправление серьезных проблем (патч, заплатка)  
>**OK** = стабильная версия (по умолчанию)  

#### (2) Ветвления для разделения по функционалу  
>**0000** Основной функционал (основные функции системы)  
>**000X** Базовый функционал (базовый набор функций и подсистем), уровень X=[1-9]  
>**00Y0** Важный функционал (набор подсистем), уровень Y=[1-9]  
>**0Z00** Дополнительный функционал (набор подсистем), уровень Z=[1-9]  
>**CZYX** Комплексный функционал, уровень C=[1-9]  

### 3. Версионность на основе [семантической нумерации версий](https://semver.org/lang/ru/)  
##### .V.AA.BB.CC[.DD] = Номера версий в формате .V.МАЖОРНАЯ.МИНОРНАЯ.ПАТЧ  
Cледует увеличивать:  
##### .AA.BB :  
>МАЖОРНУЮ версию "AA", когда сделаны изменения, "обратно несовместимые" с предыдущими версиями.  
>МИНОРНУЮ "BB" версию, когда добавлена новая функциональность, с сохранением "обратной совместимости".  
##### .CC :  
>ПАТЧ-версию, когда делаются "обратно совместимые" исправления.
##### .DD :  
>Дополнительные обозначения могут использоваться как дополнения к V.МАЖОРНАЯ.МИНОРНАЯ.ПАТЧ формату. Используются для создания предрелизных (тестовых и ожидающих одобрения) версий и обозначения  вариантов исполнения (билд-метаданных).  

[Регулярные выражения](https://regex101.com/) для корректных номеров версий с дополнительными обозначениями:  
`.DD = [.][0-9a-zA-Z]{1,4}`  
`.V.AA.BB.CC[.DD] = [.][Vv][0-9]{1,4}[.][0-9]{1,4}[.][0-9]{1,4}[.][0-9a-zA-Z]{1,4}`  

### 4. Приоритеты поставленных задач  
#### Приоритеты оптимизации качества разработки (Q=качественно, T=быстро, G=дешево, R=риски)  
>!!!! = !!!!качество (отлично, без вариантов)  
>!!!? = !!!качество, ? (хорошо+выбор QTGRx1)  
>!!?? = !!качество, ?? (средне+выбор QTGRх2)  
>!??? = !качество, ??? (плохо+выбор QTGRх3)  
>???? = качество, ???? (неуд+выбор QTGRх4)  

### 5. Сохранение черновиков и промежуточных версий файлов, частота коммитов в общий серверный репозитарий  
#### (1) Новая ветвь (branch)  
>При постановке новой задачи (issue) команде, либо по мере необходимости  
#### (2) Совместная работа над файлами  
>Черновой вариант: при сохранении в общий репозитарий: не чаще 4 раз в сутки (утро, полдень, вечер, ночь)  
>Оптимальный вариант: 2-3 раза в неделю (понедельник&четверг | пн&ср&пт)  
#### (3) Объединение ветвей  
>По необходимости и готовности к объединению  
#### (4) Завершение этапов, задач, сохранение ветвей и истории изменений  
По окончанию сроков исполнения & готовности задач:    
> сохранять финальные версии файлов в стабильной ветви "OK"  
> ??? сохранять альтернативные версии файлов с пометкой "JinC" (Just in Case)  
> ??? сохранять ветви с еженедельной историей изменений с пометкой "WeekStory"   

### 6. Ориентировочный недельный график  
>Подведение итогов недели и корректировка планов: вт  
>День ЗОЖ, спорта, укрепление команды.: чт  
>Вечер неЗОЖ (коммиссии, праздники, гости и т.п.).: пт  
