# Описание формата разработки и поддержки решений  
Назначение: рекомендуется использовать для подготовки к проекту, проектной работе, разработке решений и проектной документации, внедрения, эксплуатации  

## 0. Ориентировочный недельный график  
> Корректировка планов, Плановые работы: еженедельно, пн   
> Плановые работы: еженедельно, вт   
> Плановые работы, Подведение итогов недели: еженедельно, ср   
> День собственных проектов, творчества, ЗОЖ, спорта, укрепления команды.: чт   
> Планы на неделю, Доделки по недоделкам, Внеплановые работы, Вечер неЗОЖ: пт   

## 1. Проектная работа   
### 1.1. Проект (Project)  
Цели проекта  
Задачи проекта  
Применение проекта  
Жизненный цикл проекта  
Группа проектов  

### 1.2. Задачи проекта (issue)  
Определение  
Автор  
Ответственный (Assignees)  
Описание  
Исходные данные  
Требования к результату  
Приоритеты  
Этапы и метки задачи (Labels)  
История задачи  
Результат выполнения задачи  
Закрытие задачи  

### 1.3. Вехи (Milestones) и сроки проекта  
Веха: заданный момент времени
На GitHUB возможно создать веху указав к ней дату, заголовок и описание. 
Созданную веху можно редактировать и закрыть.
К задаче (issue) можно привязать 1 веху.

## 2. Жизненный цикл  
### 2.1. Проекты  
#### (0) Запрос на развитие  
#### (1) Подготовка  
#### (2) Разработка  
#### (3) Тестирование, правка, оптимизация  
#### (4) Сопровождение (поддержка) проекта  
> Прием заявок (задач)  
> Классификация заявок (задач)  
> Отработка заявок (задач)  
#### (5) Внедрение      
#### (6) Использование     
#### (7) Итоги использования и история успеха   
#### (8) Сбор и накопление информации по проекту      
#### (9) Завершение  

### 2.2. Задачи  
#### Правила присвоения имен задачам:  
Коротко обозначить: подсистему, функционал и цель создания задачи  
#### Правила создания первичного описания задачи:  
(1) Обозначить цели выполнения задачи  
(2) Поставить соответствующие метки (Labels):  
>**LOOP** = похожая задача уже существует  
>**0REQ** = запрос на создание, разработку, выполнение работ  
>**1PRE** = подготовка к разработке, сбор исходных данных, систематизация, анализ, формирование требований и подготовительной документации  
>**2DEV** = развитие (разработка), создание прототипа, разработка нового функционала  
>**2RED** = правки, модификации, изменения, оптимизация существующего функционала  
>**3TST** = тестирование прототипа, функционала, изменений, совместимости  
>**3RUN** = тестовая эксплуатации  
>**4SUP** = осуществляется техподдержка (фиксация, диагностика и решение проблем в стабильной версии)  
>**4BUG** = исправление неточностей и небольших ошибок  
>**4RAT** = исправление серьезных ошибок и проблем (патч, заплатка)  
>**4ASK** = нужен ответ на вопрос или консультация  
>**OK** или **5+OK** = проверенная версия для использования  
>**6REQ** = запрос на стандартизацию/интеграцию   
>**6API** = доработка/стандартизация для интеграции с другими системами   
>**7SUC** = история успеха  
>**8INF** = запрос на предоставление информации  
>**9EVO** = завершение: задача поглощена или перешла в другую задачу  
>**9END** = завершение: поддержка, разработка или работы приостановлены или отменены  

(3) Описание планируемого практического применения результата работ  
(4) Ссылки на проект  
(5) Ссылки на смежные задачи (по смежным подсистемам, функционалу и т.д.)  
#### Собрать и предоставить первичные исходные данные по задаче:  
(1) Документация и описания, необходимые для понимания задачи  
(2) МетаДанные  
#### Сформулировать требования к результату выполнения задачи:  
(1) Обозначить необходимые и достаточные  требования: 
>* к результату и функционалу  
>* к решению  
>* к составу работ  
>* к срокам исполнения  

(2) Обозначить предварительный бюджет задачи:  
(3) Обозначить риски и неопределенности (неполнота исходных данных, возможные изменения исходных данных, требований, сроков, решения, бюджета, состава работ)  
(4) Обозначить приоритеты при выполнении задачи (качество, сроки, бюджет, риски) 
#### Обозначить приоритеты задачи  
Приоритеты оптимизации качества разработки (Q=качественно, T=быстро, G=дешево, R=запас на риски)  
>!!!! = !!!!качество (отлично, без вариантов)  
>!!!? = !!!качество, ? (хорошо+выбор QTGRx1)  
>!!?? = !!качество, ?? (средне+выбор QTGRх2)  
>!??? = !качество, ??? (плохо+выбор QTGRх3)  
>???? = качество, ???? (неуд+выбор QTGRх4)  
#### История задачи  
Сохраняется в комментариях задачи
#### Результат выполнения задачи   
Требованиям также присваивается номер версии, как и результату, к которому они применяются.  

Результат, удовлетворяющий изначальным требованиям, с учетом их последующей корректировки.  
#### Закрытие задачи   
Закрытие задачи можно сделать автоматическим, если привязать ее завершение к завершению запросо на добавление изменений.   

## 3. Решения
**Решение** (solution) - это комплекс модулей, совместимых между собой, имеющих взаимосвязанные планы развития и связанных межлу собой в единую группу, позволяющую создавать системы на их основе (на основе модулей решения), обладающие функционалом включенных в него модулей    
**Продукт** (product) - это набор готовых модулей решения, не требующей доработки и настройки для создания **типовой системы** или требующей минимальной доработки и настройки для создания **системы**   
**Модуль** (module) - это компонент решения, обладающий заданным набором функционала   
**Версия** (version) - один из вариантов исполнения    
**Релиз** (release) - версия, в которую далее запрещено вносить изменения, за исключением исправлением ошибок   

### 3.1. Состав решения   
### 3.2. Жизненный цикл решения   
#### (0) Запрос на создание, Начало финансирования разработки   
>**LOOP** = похожая задача уже существует  
>**0REQ** = запрос на создание, разработку, выполнение работ  
#### (1) Подготовка к разработке    
>**1PRE** = подготовка к разработке, сбор исходных данных, систематизация, анализ, формирование требований и подготовительной документации  
#### (2) Разработка решения и создание прототипа, оптимизация и доработка решения   
>**2DEV** = развитие (разработка), создание прототипа, разработка нового функционала  
>**2RED** = правки, модификации, изменения, оптимизация существующего функционала  
#### (3) Тестирование решения и прототипа    
>**3TST** = тестирование прототипа, функционала, изменений, совместимости  
>**3RUN** = тестовая эксплуатации  
#### (4) Сопровождение/техподдержка решения   
>**4SUP** = осуществляется техподдержка (фиксация, диагностика и решение проблем в стабильной версии)  
>**4BUG** = исправление неточностей и небольших ошибок  
>**4RAT** = исправление серьезных ошибок и проблем (патч, заплатка)  
>**4ASK** = нужен ответ на вопрос или консультация  
#### (5) Выпуск работающей и протестированной версии (релиза)   
>**OK** или **5+OK**= проверенная версия для использования  
#### (6) Стандартизация и интеграция решения     
>**6REQ** = запрос на стандартизацию (интеграцию) решения   
>**6API** = разработка компонентов для интеграции с другими системами   
#### (7) История успеха   
>**7SUC** = история успеха  
#### (8) Ипользование решения    
>**8INF** = запрос на предоставление информации  
#### (9) Завершение разработки   
>**EVO** или **9END** = завершение: поддержка, разработка или работы приостановлены или отменены  
> Завершение продаж   
> Завершение сопровождения   
> Завершение финансирования   
> Завершение использования   
> Утилизация    

### 3.3. Репозитарий решения   
#### Термины  
**Каталог (папка) репозитария** - папка (каталог) решения, где размещены файлы и папки репозитария.  
**Конфигурация репозитария** - хранится в служебных файлах и папках репозитария репозитария.  
>**Файлы** - указатель на набор данных, сохраненных в файловой системе под одним именем.  
>**Папки** или **Каталоги** - указатель на набор файлов, сохраненных в файловой системе под одним именем.  
**НЕиндексируемые файлы** - это файлы репозитария, для которых в репозитарии не применяется контроль версий (т.е. для всех версиях репозитария существует только одна версия такого файла).  
> В GIT Список таких файлов задается в файле ".gitignore"  
**Индексируемые файлы** - это файлов репозитария, для которых в репозитарии применяется контроль версий (т.е. для разных версий репозитария могут существовать более одной версии такого файла).  
**Снимок репозитария** (snapshot) или **Версия** - вариант сохраненных в репозитарии файлов, относящихся к одной версия репозитария.  
**Указатель на снимок** - это ссылка на снимок одной из версий репозитария.  
**Ветвь** (Branch) - это название цепочки указателей на последовательные снимки репозитария, сохраненные в соответствие с порядком их создания.  
**Указатель на ветвь** - это указатель на самый свежий снимок в ветви. При сохранении изменений в ветви репозитария сохраняется указатель на новый снимок репозитария.  
**Дерево** (TREE) - это список ветвей репозитария.  
**Метка** (TAG) - именованный указатель на версию репозитария (аналогично ветви, но без обновления указателей на новые версии репозитария)  
**Авторская метка** (aTAG) - это метка с указанием автора, его электронной почты, даты и комментария  
**Подписанная авторская метка** (sTAG) - это авторская метка, подтвержденная "секретным кодом" автора (GPG)  

#### Действия с локальным репозитарием  
**Инициализация** (init) инициализация репозитария в каталоге.  
**Добавление** (add) файлов и папок репозитарии в список индексируемых репозитарием.  
**Игнорирование** репозитарием файлов (создание списка игнорируемых репозитарием файлов (.gitignore)).  
**Сохранение изменений** (commit) в репозитарии - это создание нового снимка репозитария и добавление его к ветви репозитария.  
**Извлечение файла** (checkout) из репозитария - это получение последней версии файла из ветви репозитария.  
**Объединение ветвей** (merge) репозитария -  объединение в единое целое файлов из снимков, относящихся к разным ветвям репозитария.  

#### Действия с репозитарием хранилища  
**Клонирование** (clone) репозитария на компьютер пользователя - это копирование репозитария из хранилища.  
**Синхронизация** (fetch) локального репозитария с репозитарием хранилища - это получение локальным репозитарием данных репозитария из хранилища.  
**Получение** (pull) репозитария на компьютер пользователя - это получение данных репозитария из ветви в хранилище и объединение их ветвью локальном репозитарии.  
**Отправка** (push) локального репозитария в хранилище - это отправка последней версии снимка из ветви репозитария в хранилище.  
**Запрос на добавление изменений** (pull request) -  запрос на добавление нового снимка из одной ветви репозитария в другую.  
**Запрос на объединение ветвей** (merge request) -  запрос на объединение файлов из последних версий снимков, относящихся к двум разным ветвям репозитария, в одну ветвь.  

#### Каталоги (папки) решения  
>**./** Корневая папка (каталог) решения  
>**./BOOK** Для проектной и эксплутационной документации, книг, описаний  
>**./TOOL** Инструментарий  
>**./GOLD** Условия и результат оплаты  
>**./WARE** Решение  

#### Функционал решения или модуля (pack)  
>**0000** Основной функционал (основные функции системы)  
>**000X** Базовый функционал (базовый набор функций и подсистем), уровень X=[1-9]  
>**00Y0** Важный функционал (набор подсистем), уровень Y=[1-9]  
>**0Z00** Дополнительный функционал (набор подсистем), уровень Z=[1-9]  
>**CZYX** Комплексный функционал, уровень C=[1-9]  

### 3.4. Ветви (branch), версии (version), этапы (stage) и метки (tag)  
#### Правила присвоения имен ветвям и меткам:  
(0) Название решения (solution), продукта (product) или системы (system)  
(1) Название модуля (module)   
(2) Номер версии решения/модуля (version)  
(3) Расширенное обозначение функционала (pack) решения или модуля = опционально  
(4) Стадия разработки (stage) = опционально  
(5) Приоритет разработки (priority) = опционально   
(6) Подпись (sign) разработчика   
Примеры назначения имен ветвям и меткам:  
> solution.version.stage.priority.sign (для основного функционала решения)  
> solution.pack.version.stage.priority.sign   
> module.version.stage.priority.sign (для основного функционала модуля)  
> module.pack.version.stage.priority.sign     
> 

### 3.5. Обозначение номера версии решений и модулей  
На основе [семантической нумерации версий](https://semver.org/lang/ru/)  
>solution.pack.version  
>module.pack.version  
>.V.AA.BB.CC[.DDD] = Номера версий в формате .V.МАЖОРНАЯ.МИНОРНАЯ.ПАТЧ[.ТИП]   

Cледует увеличивать:  
>.AA.BB :  
МАЖОРНУЮ версию "AA", когда сделаны изменения, "обратно несовместимые" с предыдущими версиями.  
МИНОРНУЮ "BB" версию, когда добавлена новая функциональность, с сохранением "обратной совместимости".  
>.CC :  
ПАТЧ-версию, когда делаются "обратно совместимые" исправления.  
>.DD :  
ТИП, предназначение или вариация версии (test, main, full, special, portable)   
Дополнительные обозначения могут использоваться как дополнения к V.МАЖОРНАЯ.МИНОРНАЯ.ПАТЧ формату. Используются для создания предрелизных (тестовых и ожидающих одобрения) версий и обозначения  вариантов исполнения (билд-метаданных).  
[Регулярные выражения](https://regex101.com/) для корректных номеров версий с дополнительными обозначениями:  
`.DD = [.][0-9a-zA-Z]{1,4}`  
`.V.AA.BB.CC[.DD] = [.][Vv][0-9]{1,4}[.][0-9]{1,4}[.][0-9]{1,4}[.][0-9a-zA-Z]{1,4}`  

### 3.6. Этапы жизненного цикла решения (stage) в обозначениях версий решений и модулей     
Выполняется аналогично присвоенной метки задачи:  
> 0REQ   
> 1PRE   
> 2DEV, 2RED   
> 3TST, 3RUN   
> 4ASK, 4BUG, 4RAT, 4SUP   
> OK = версия для использования (по умолчанию)   
> 6REQ, 6API   
> 7SUC       
> 8INF  
> 9END  
> 

### 3.7. Сохранение черновиков и совместная работа     
Сохранение черновиков и промежуточных версий файлов, частота коммитов в общий серверный репозитарий   
#### (1) Новая ветвь (branch)   
> Может быть создана при взятии в работу новой задачи (issue)   
> > При целесообразности  и по мере необходимости   
> 
#### (2) Совместная работа над файлами   
> Черновой вариант: при сохранении в общий репозитарий: не чаще 4 раз в сутки (утро, полдень, вечер, ночь)  
> Оптимальный вариант: 2-3 раза в неделю (вечером в понедельник&среду | пн&ср&пт)  
>
#### (3) Объединение ветвей  
> При целесообразности и готовности к объединению  
> 
#### (4) Завершение этапов, задач, сохранение ветвей и истории изменений  
По окончанию сроков исполнения & готовности задач:  
> сохранять финальные версии файлов в стабильной ветви "OK"  
> сохранять альтернативные версии файлов в версиях с пометкой "JinC" (на всякий илучай = Just in Case) и описанием особенностей   
> ??? сохранять ветви с еженедельной историей изменений с пометкой "WeekStory"   
> 


3x/\
