---
related:
- basics/create-plan-activity.md
- basics/complete-activity.md
- basics/analyse-detailed-activity.md
- basics/create-record.md
- basics/calendar.md
- basics/coach-dashboard.md

---
# Создать соревнование

**Соревнование** - запись календаря, содержащая информацию о запланированном или завершенном соревновании.

В этом разделе:
* [Запланировать соревнование](#create);
* [Отразить факт выполнения соревнования вручную или автоматически](#complete);
* [Прикрепить нужную фактическую тренировку к соревнованию](#splitmerge).

### Запланировать соревнование{#create}

В Стаминити можно создать соревнования по триатлону, бегу, плаванию,  велоспорту и лыжным гонкам.

Для создания соревнования нажмите "Добавить" в выбранном дне календаря и выберите вид спорта для соревнования:

![Визард добавления записей в календарь Staminity](https://264710.selcdn.ru/assets/images/periodization/wizard-competition.png)

При создании соревнования необходимо указать:
![Добавить соревнование в Staminity](https://264710.selcdn.ru/assets/images/periodization/competition-create2.png)

* **Название** - название соревнования, которое вы хотите видеть в календаре
* **Вид спорта**
* **Тип соревнования** для выбранного вида спорта. Для бега - марафон, полумарафон, 10 км, 5 км. Для триатлона - полная дистанция, 1/2 полной дистанции и т.п.
* **Приоритет**: А - ключевой старт сезона, B - один из промежуточных стартов, С - не приоритетный старт.
* **Установка тренера**

![Добавить соревнование в Staminity](https://264710.selcdn.ru/assets/images/periodization/competition-create.gif)

Для соревнований также можно указать **целевое время или расстояние**. Для стандартных дистанций указывается плановое время, для соревнований на время - целевое расстояние. 

Планируется каждый этап соревнования отдельно. Например, в триатлоне плановое время задается для плавания, велоэтапа и бега, а также отдельно планируется время прохождения транзитных зон.

План по времени указывать не обязательно, но если он введен, то Стаминити будет использовать именно его при сопоставлении факта с планом.

![План на гонку в Staminity](https://264710.selcdn.ru/assets/images/periodization/competition-edit.gif)

### Выполнить соревнование - вручную или автоматически{#complete}

Также, как для отдельного задания, факт выполнения соревнования можно указать вручную,  либо факт будет рассчитан автоматически после загрузки выполненных занятий с часов или со смартфона.

В отличие от тренировки, в одном соревновании может быть несколько тренировок, т.к. план создается на каждый этап соревнования. При загрузке выполненной тренировки она может быть сопоставлена с ранее созданной плановой по стандартным правилам.

![Просмотр выполненного соревнования в Staminity](https://264710.selcdn.ru/assets/images/periodization/competition-completed.png)

Если к этапу соревнования будет привязана фактическая тренировка, из карточки соревнования можно будет перейти и проанализировать этап детально, как [обычную тренировку](/basics/analyse-detailed-activity.md).


### Выполнить соревнование - связать фактическую тренировку с этапом соревнования{#splitmerge}

Если выполненная тренировка не была автоматически связана с этапом соревнования, это можно сделать вручную.

Для связи фактической тренировки с этапом соревнования перетащите ее на нужный этап:

![Вручную связать факт с соревнованием](https://264710.selcdn.ru/assets/images/_new/activity/merge-competition.gif)

Если факт был связан с этапом соревнования по ошибке, можно открепить фактическую тренировку от планового этапа. Для этого откройте этап соревнования на просмотр и в контекстном меню тренировки выберите пункт "Открепить фактические данные". 

![Открепить факт от соревнования](https://264710.selcdn.ru/assets/images/_new/activity/split-competition.gif)