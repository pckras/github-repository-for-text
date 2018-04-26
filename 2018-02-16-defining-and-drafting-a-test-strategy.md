В [учебных программах](/2016-08-14-educational-programs-exam-questions-and-literature.md) по дисциплине "Обеспечение качества и тестирование программ" есть вопрос "Определение и составление тестовой стратегии. Понятие тестовой стратегии". В программе обучения продвинутого уровня International Software Testing Qualifications Board "Руководитель тестирования" указано на необходимость уметь "Проанализировать предоставленные примеры политик и стратегий тестирования, и создать главный план тестирования, уровневый план тестирования, и другие завершенные и соответствующие этим документам рабочие продукты тестирования", "Описать на примерах, как стратегия тестирования влияет на активности тестирования".

Собрал подборку материалов по теме.

«Тестирование Дот Ком, или Пособие по жестокому обращению с багами в интернет-стартапах», **Роман Савин**, Москва: Дело, 2007, 266-279 страницы:

> ![](https://lh3.googleusercontent.com/FV_BvGcARRzB8eZphORP-LsJcduZUoixNbMlq1B55JDwt7WRhIVHU3ZFVhJ-2aLvWl1oj71DnuwOi0YfjYtizckLtfSwK4pfhjV3DYw3fjclJFZhc4sryLNoapH2VLOpcqXDNepkRKwzbAf6ku1pZBrxp0m3Psgez6ztKmJFVftOdsQHGQghOb0A-vCHXNi1mD1bOd3j1n2sXPrupccXJ_Dq-llGph11eSMfxpDoQWfGLBBDb8dPXlSec_Gsa0o4vuKmwWwBF01Qcya4cQoEbILOcr6OmgFB29DaOxtih8Dzn_G-KZQyD1Oe11H--LF2pcVhiZHY9TS6qgT-LRPDhV57tCSeWSdrpJEGCoECBn3vrCg_PsoxtsBehSeVAKFDTeAVkzuJdzy_0dVpsB45O0gnl9WbSXrSdRT3J11GRTI9y7deT06La8VxQM6CaNLpfGHNLJgAXfi1J-QSLwrDSh1iagwwH3v1LoawQfi4IFnlKLMi-PNTLEckbYH_8Xfft-7zTTIoISCxvzMwgkc_pzB4wzlfpvmmd8oq2Z2UNMnjzaTr5mdcXCiQIGteIjfn8jc9eT7OW4rydVQOoWrUwPli4ghT6xHjtPOhnWit8tBu4RXsCXRDjju5XYmHrEMHL9Tdiz-tYrPAtq-YI5OTmTv8cE-NTN0V=w700-h406-no)

> Что такое тест-план? Если вы спросите тестировщиков разных компаний о том, что идет под именем "тест-план" в их компа- ниях, то ответ часто будет варьироваться:
> - иногда тест-планом называют тест-комплект,
> - в других случаях тест-планом называют пару мыслей о тестировании, набросанных на полях журнала "Playboy",
> - в третьих случаях тест-планом называют текстовый документ, содержащий выдержки из спека, глядя на которые и проводится тестирование (такое тоже бывает сплошь и рядом),
> - есть еще и четвертые, и пятые случаи.

> Вот концептуальная вещь:
> - тест-кейс нужен для сравнения фактического результата с ожидаемым результатом;
> - тест-комплект — это логическая оболочка для хранения тест-кейсов;
> - тест-план — это документ, обобщающий и координирующий тестирование.

> Я обычно ограничиваюсь тест-комплектами и создаю тест-план, если возглавляю проект с участием других тестировщиков.

> Давайте рассмотрим элементы, которые вы можете использовать в тест-планах.

> Кстати, вовсе не обязательно использовать все элементы:
> 1. Вы можете взять элементы (и/или идеи из них) иинтегрировать их в свои тест-комплекты;
> 2. Вы можете использовать тест-план в усеченном виде.
Итак...

> ЭЛЕМЕНТЫ ТЕСТ-ПЛАНА

> **1. Название тест-плана, имя автора и номер версии**.
>> _Например
>> «Тест-план проекта "Новые алгоритмы для поиска"». Автор Т. Черемушкин. Версия 2._

> **2. Оглавление с разделами тест-плана**:
>> _Например
>> Введение стр. 2
>> Документация с требованиями к ПО стр. 3 и т. д._

> **3. Введение**, в котором мы приводим информацию о сути и истории тестируемого проекта.

> **4. Документация с требованиями к ПО** — здесь мы перечис- ляем имена, номера и приоритеты спеков и/или другой докумен- тации, определяющей тестируемые фича.

> **5. Фичи, которые будут тестироваться**, перечисляем и, если нужно, комментируем. Каждой фиче назначается приоритет.

> **6. Фичи, которые НЕ будут тестироваться**, перечисляем и объ- ясняем, почему НЕ будут тестироваться.
>> Например,
>> _частью спека #9172 "Улучшение безопасности платежных транзакций" являются требования к скорости работы веб-сайта (performance). Допустим, у нас нет ни специалиста, ни ПО для тестирования скорости работы, и если мы не собираемся их нанять и приобрести, то указываем, что перформанс тестироваться не будет, так как нет ресурсов._

> **7. Объем тестирования** — виды тестирования, которые мы бу- дем проводить, и разъяснения к ним.
>> _Например
>> "Системное тестирование будет исполняться для проверки всего флоу оплаты, начиная от добавления книги в корзину и заканчивая проверкой значений базы данных и подтверждением от тест-машины вендора"._

> **8. Тест-документация** — перечисление тест-документации, ко- торая должна быть создана для данного проекта
>> _Например,
>> "Тест-комплект по тестированию опека #1288. Тест-комплект по тестированию спека #3411"_.

> **9. Тест-тулы** — функциональности тест-тулов, которые должны быть созданы для тестирования проекта.

> **10. Критерий начала/завершения** — те самые критерии, о кото рых мы говорили минуту назад:
> - критерий начала подготовки к тестированию;
> - критерий завершения подготовки к тестированию;
> - критерий начала исполнения тестирования;
> - критерий завершения исполнения тестирования.

> **11. Допущения** — список допущений, которые мы сделали при составлении данного тест-плана и которые сделаем при тестировании.
>> _Например,
мы допускаем (предполагаем), что код будет заморожен в срок, без задержки_.

> **12. Зависимости** — список вещей (с пояснениями), от которых зависит та или иная часть тестирования.
>> _Например,
покупка новых тест-машин,
лицензия на осуществление платежных операций на территории Великобритании_.

> **13. "Железо" и ПО** — список и конфигурации "железа" и ПО, которые будут использоваться при тестировании.

> **14. Условия приостановки/возобновления тестирования** — это
условия, при которых тестирование должно быть остановлено/ продолжено.
>> _Например,
к условию приостановки можно отнести количество П1 багов, при ко- тором (и/или после которого), по мнению автора (-ров) тест-плана, дальнейшее продолжение тестирования не имеет смысла (например, 7 П1). Соответственно условием возобновления должно быть количе- ство оставшихся П1 багов (после ремонта и регрессивного тестирова- ния), которое позволяет возобновить тестирование (например, 2 П1)_.

> **15. Ответственные лица** — подробный список товарищей (про- дюсеров, программистов, тестировщиков и пр.), контактная информация и обязанности каждого из них. Такой список может включать лиц со стороны вендора.

> **16. Тренинг** — тренинг, необходимый для данного проекта.
>> _Например,
при соответствующей ситуации нужно указать, что для создания тест- кейсов тестировщику необходимо прослушать семинар "Банковская система США"_.

> **17. Расписание** — сроки, имеющие отношение к тестированию данного проекта:
> - дата замораживания спеков;
> - дата начала подготовки к тестированию;
> - дата завершения подготовки к тестированию;
> - дата интеграции и замораживания кода;
> - дата начала тестирования новых фича;
> - дата завершения тестирования новых фича;
> - дата начала регрессивного тестирования;
> - дата завершения регрессивного тестирования.

> **18. Оценка риска** — предположение о том, как и что может пой ти по неправильному пути и что мы в этом случае предпримем.
>> _Например,
если мы не успеваем закончить тестирование (не выполняем требование "Условия завершения", например, "все тест-кейсы исполнены") в срок, то придется задерживаться на работе и приходить в офис в вы- ходные и праздники.
> Кстати, если народ приходит в выходные и праздники, то компания должна, по крайней мере, кормить его обедом._

> **19. Прочие положения** — вещи, не вошедшие в тест-план, о которых неплохо было бы упомянуть.

> **20. Утверждения** — это подписи лиц, которые утвердили тест- план. Чем больше будет таких подписей, тем лучше. По крайней мере, нужны подписи менеджера тестировщика, составившего план, самого тестировщика, продюсера и программиста.

> **21. Приложения** — например, расшифровка терминов и аббревиатур, используемых в тест-плане.

IEEE Standard for Software and System Test Documentation, **IEEE Std 829-2008**. 35-42 страницы:

> Master Test Plan Outline (full example)
1. Introduction
1.2. Scope
1.3. References
1.4. System overview and key features
1.5. Test overview
1.5.1 Organization
1.5.2 Master test schedule
1.5.3 Integrity level schema
1.5.4 Resources summary
1.5.5 Responsibilities
1.5.6 Tools, techniques, methods, and metrics
2. Details of the Master Test Plan
2.1. Test processes including definition of test levels
2.1.1 Process: Management
2.1.1.1 Activity: Management of test effort
2.1.2 Process: Acquisition
2.1.2.1: Activity: Acquisition support test
2.1.3 Process: Supply
2.1.3.1 Activity: Planning test
2.1.4 Process: Development
2.1.4.1 Activity: Concept
2.1.4.2 Activity: Requirements

[«Как тестируют в Google»](https://www.piter.com/product/kak-testiruyut-v-google), **Джеймс Уиттакер, Джейсон Арбон, Джефф Каролло**. - СПб.: Питер, 2014. 287/320 страниц:

> ![](https://lh3.googleusercontent.com/qRRXtsKLqoyaEOIKS5p4LsNLT8uiTZMPpPvEeojjOE2yo8zmRkztJVve11mWKB2X2EkJDNhQXzYlhY9wy-wesYUNH14rDp5nRZDz4Qw-Ynym1t3bs5huwojuJeIXbVgaDWJnA3ffMOPOmXb3DkPW5Zf2tgTJFK1xW4bpyKcqSYIkAX3_MSmxjzHyLQ6QR22P3i1-ZQ_Edr8jF3Rm1YcCosuRjdlcrDIzssYoCFDB5aVgZrEy9ZxkuFIyIuLnXLpvGlWQcra4wERvF5d94-Fkn2e9WR9231EvJ6nDTUegXH7G1cj-V-ZNHh663xt5SYmxhi0ky9_7Vsft4Q6ojU738cEFp5NQd6OCgDmIt3S82DjWJDlqc-0MD6PUGTajgzigLyD3cL5y4Ow_98F7cx5xMpzb1R8E7QhRFE10UtVotosZ0AKcTl62xeFznK4OrkpRXHYImAq4l1lmJe1k1Is9j1e7NH2DevCiR4JERJPuSbfVWNO71hr6H8ERwTMOanqeh793cqZX2Wn-Iv19_4SnOytu6VKzm52iWWfDWJIO1muhM1JzuQE4N0P80xEZsY8jHDNdnyYMlb7xxMXahbAmwrdo0uzLfOkYNqfKpUVm0DhmnTQHcd0YJIcaTQa4epKmtyeTiGYKwbvQwpJTLozp7yqp47utHIne=w700-h406-no)

> Тест-план для Chrome OS

> Обзор тем

> Анализ рисков

> Непрерывное тестирование каждой сборки

> Ежедневное тестирование лучших сборок

> Тестирование перед выпусков

> Ручное и автоматизированное тестирование

> Разработка и качество тестов

> Каналы выпуска

> Обратная связь

> Репозитории тест-кейсов

> Панели мониторинга тестов

> Виртуализация

> Производительность

> Нагрузочное тестирование, продолжительное тестирование и тестирование стабильности

> Фреймворк выполнения тестов Autotest

> Производители железа

> Лаборатория проверки оборудования

> Фермы для сквозных автотестов

> Тестирование AppManager в брузере

> Тестируемость браузера

> Оборудование

> График

> Ключевые моменты тестирования

> Необходимые документы и ресурсы

15.02.2018