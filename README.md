## Шаблон репозитариев: newRepositary
### 1. Папки репозитария:
**BOOK** Для документации, книг, описаний

**TOOL** Разработанный инструментарий

**GOLD** Условия и инструменты для оплаты за использование инструментария

### 2. Шаблон нового репозитария с набором ветвлений (branches)
#### (1) Основные ветви (branches) для разделения на этапы разработки и использования:
**PRE** = подготовка

**DEV** = разработка

**TST** = тестирование

**DBF** = исправление багов

**DOK** = разработано, проверено, согласовано

**RUN** = в тестовой эксплуатации

**SUP** = работающее решение с техподдержкой

**main** = работающее решение


#### (2) Дополнительные ветвления
**0000** Базовый функционал

**000X** Основной функционал, уровень X={1...9}

**00Y0** Важный функционал, уровень Y={1...9}

**0Z00** Дополнительный функционал, уровень Z={1...9}

**MZYX** Смешанный функционал, уровень M={1...9}

#### (3) Нумерация версий в ветках
##### V.AA.BB.CC = Номера версий в формате МАЖОРНАЯ.МИНОРНАЯ.ПАТЧ
Учитывая номер версии МАЖОРНАЯ.МИНОРНАЯ.ПАТЧ, следует увеличивать:
##### AA = {0...99999}:
МАЖОРНУЮ версию, когда сделаны обратно несовместимые изменения API.
МИНОРНУЮ версию, когда вы добавляете новую функциональность, не нарушая обратной совместимости.
##### BB = {0...99999}:
ПАТЧ-версию, когда вы делаете обратно совместимые исправления.
##### CC= {0...99999}:
Дополнительные обозначения для предрелизных и билд-метаданных возможны как дополнения к МАЖОРНАЯ.МИНОРНАЯ.ПАТЧ формату.
##### (С) https://semver.org/lang/ru/

### 3. ТЭГИ для задач:
#### Приоритеты оптимизации качества разработки (Q=качество, T=сроки, G=финансирование, R=?=риски)
QQQQ = !!!!качество,  (отлично)

QQQ? = !!!качество, ! (хорошо)

QQ?? = !!качество, !! (нормально)

Q??? = !качество, !!! (средне)
