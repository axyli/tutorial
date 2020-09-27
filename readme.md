#### Интервью
https://www.websequencediagrams.com
##### Какие нотацие описания бизнес-процессов вы знаете

Основные нотации бизнес-процессов
* Блок-схема (Flowchart)
* Блок-схема с дорожками (Swimlanes, Cross functional flowchart)
* Процедура
*  Диаграмма деятельности (Activity diagram)
* Диаграмма последовательности (Sequence diagram)
*  IDEF0
* EPC
* BPMN


##### Требования

1. Методы сбора требований
    * Мозговой штурм
    * Интервьюирование пользователей
    * Погружение в среду пользователя
    * Изучение аналогов
    * Изучение «книги жалоб и предложений»
    * Разговор с командой поддержки
    * Изучение усовершенствований, сделанных пользователями
    * Совместный семинар
    * Демонстрация прототипа заинтересованным лицам
    
https://habr.com/ru/company/simbirsoft/blog/307844/

#### UserStory UseCase(Пользовательсике истории Варианты использования)

###### UserStory

User story описывает, что делает пользователь определенной роли для достижения результата, и что нужно сделать разработчику, чтобы воплотить эту задачу в жизнь.
Как правило используется шаблон:  
``As a/an <Название роли>, I want to <Цель, Действие>, so that <Ожидаемый результат>, to do <Что нужно сделать разработчику>``

###### UseCase
UseСases описывает поведение пользователя по шагам при взаимодействии с разрабатываемым продуктом.

###### Отличия

* Пользовательские Истории – это исходные требования от заказчика о целях пользователей в общем виде. Каждая Пользовательская История – это повод к обсуждению с заказчиком.
* Пользовательские Истории ни в коем случае не являются конечными требованиями к системе. Ошибкой считать, что Пользовательские Истории должны «как есть» помещаться в «баклог». На основе пользовательских историй обязательно должны быть сформированы четкие требования к системе (зачастую, варианты использования).
* Нет цели – сформулировать требование по «шаблону» Пользовательской Истории. Если известны конкретные требования к системе, то перефразировать их под «шаблон» не имеет смысла. Шаблон, предложенный Майком Коном, не является неотъемлемым свойством Пользовательских Историй, а есть лишь подсказка к сути их содержания.
* Основное отличие Пользовательских Историй от Вариантов Использования заключается в том, что Истории являются исходными требованиями, а Варианты Использования – конечными.
* Пользовательские Истории, как правило, пишутся в более свободном формате, чем Варианты Использования. Глядя на пользовательские истории, зачастую нельзя однозначно определить критерии их проверки. Пользовательские Истории, в основном, являются только идеями требований; в то время как Варианты Использования есть полноценные требования к системе.
* Название каждого Варианта Использования (ВИ) представляет собой краткую формулировку одной из целей пользователя и есть законным требованием к системе уровня «цели пользователя». Детализация же ВИ (его описание) может быть представлена как в виде пошаговых сценариев, так и в виде общего текста.
* При сборе требований к коробочному продукту (где заказчиком являемся мы же) эффективно сразу начинать с перечисления Вариантов Использования, без предварительного написания Пользовательских Историй.

##### Жизненный цикл требований

* Начинается с представления бизнес-потребностей как требований;
* Продолжается в ходе развития Решения;
* Заканчивается, когда Решение и требования списываются (утилизируются).
Управление требованиями не заканчивается после того, как Решение реализовано. На протяжении всего срока эксплуатации Решения, требования по прежнему представляют ценность, когда они управляются надлежащим образом.
В рамках области знаний по управлению жизненным циклом требований, концепция жизненного цикла отделена от методологии или процесса, который используется для управления работой по бизнес-анализу. Жизненный цикл относится к существованию различных фаз и состояний, через которые требования проходят как часть любых изменений. Требования могут находиться в нескольких состояниях одновременно.

##### Техническое задание
 
Техническое задание, как термин в области информационных технологий – это юридически значимый документ, содержащий исчерпывающую информацию, необходимую для постановки задач исполнителям на разработку, внедрение или интеграцию программного продукта, информационной системы, сайта, портала либо прочего ИТ сервиса.

**Структура ТЗ**
1. Общие сведения
1. Назначение и цели создания (развития) системы
1. Характеристика объектов автоматизации
1. Требования к системе
    * Требования к системе в целом:
    * Требования к функциям (по подсистемам):
    * Требования к видам обеспечения:
1. Состав и содержание работ по созданию системы
1. Порядок контроля и приемки системы
1. Требования к составу и содержанию работ по подготовке объекта автоматизации к вводу системы в действие
1. Требования к документированию
1. Источники разработки

Если вркатце: Что делаем? Для чего? Как поймем, что сделали? Сколько стоит каждый пивот?

##### Информационная архитектура

Информационная Архитектура (ИА) — совокупность методов, схем организации и представления информации, которые направлены на систематизацию информации для помощи пользователям находить и работать с нужными данными.