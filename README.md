# Search (general)

| Name | Link | Commentary |
|---|---|---|
| The Art of Searching | https://youtu.be/yst6VQ7Lwpo | Неплохой вводный доклад о классических подходах к Kornev полнотекстовому поиску |
| Как устроен поиск | https://habr.com/ru/company/oleg-bunin/blog/310208/ | Рассказ о том, как устроен поиск от Алексея Аксенова, автора Sphinx |
| Как устроен поиск | https://habr.com/ru/company/hh/blog/413261/ | Обзорная статья от headhunter |
| The Anatomy of a Large-Scale Hypertexual Search Engine | https://snap.stanford.edu/class/cs224w-readings/Brin98Anatomy.pdf | Основополагающая статья неких Sergey Brin и Larry Page о Google |
| Introduction to Information Retrieval (Manning & Schutze) | https://nlp.stanford.edu/IR-book/information-retrieval-book.html | Классическое введение в информационный поиск |
| Search Engines: Information Retrieval in Practice | https://ciir.cs.umass.edu/irbook/ | Еще одна хорошая книга по информационному поиску |
| Устройство поисковых систем: базовый поиск и инвертированный индекс | https://habr.com/ru/post/545634/ | Обзорная статья с раскрытием механики работы TF-IDF и BM25 о базовом поиске |

* https://habr.com/ru/company/vk/blog/338360/
* https://habr.com/ru/post/446530/
* https://github.com/facebookresearch/faiss
* http://searchivarius.org/personal/leonid-boytsovs-publications - публикации Леонида Бойцова, IR/DBMS/Algo 
* https://www.wsdm-conference.org/ - конференция WSDM
* https://dl.acm.org/conference/ir/proceedings - конференции ACM по информационному поиску. В первую очередь смотреть SIGIR и ECIR
* http://terrier.org/ - исследовательский поисковый движок на Java

# Lucene

| Name | Link | Commentary |
|---|---|---|
| Lucene In Action |  | Вводная книга для работы с Lucene с точки зрения пользователя |
| What is in a Lucene index? (Adrien Grand, Elasticsearch) | https://youtu.be/T5RmMNDR5XI | Доклад разработчика ElasticSearch и контребьютора в Lucene о внутреннем устройстве индекса |
| Keynote: Twitter's search architecture | https://youtu.be/AguWva8P_DI | Поиск в Twitter: внутреннее устройство |
| Faceted Search with Lucene (Shai Erera, IBM) | https://youtu.be/-CNZxkAMcKk | Краткая вводная в фасетный поиск в Lucene |
| Статьи Mike McCandless | https://dzone.com/users/887673/mikemccand.html | Автор Lucene In Action  |

# NLP/ML
| Name | Link | Commentary |
|---|---|---|
| Speech and Language Processing (Jurafsky & Martin) | https://web.stanford.edu/~jurafsky/slp3/ | Классическое введение в NLP |
| Очень краткое введение в ML от vas3k | https://vas3k.ru/blog/machine_learning/ | Прикольное и понятное описание задач в ML |
| Hands on Machine Learning | https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/ | Хорошее введние в ML с упором на практику |

# Java
## Multithreading

| Name | Link | Commentary |
|---|---|---|
| Concurrency In Practice |  | Отличная книга о многопоточности в Java на все времена |
| Java Language Specification, Chapter 17 | https://docs.oracle.com/javase/specs/jls/se7/html/jls-17.html | Самый главный документ о многопоточности в Java. Главный источник истины. |
| Close Encounters of The Java Memory Model Kind | https://shipilev.net/blog/2016/close-encounters-of-jmm-kind/ | Очень подробно об JMM от ключевого разработчика OpenJDK Алексея Шипилёва |

* https://www.1024cores.net/ 
* http://concurrencyfreaks.blogspot.com/

## JVM / Runtime
| Name | Link | Commentary |
|---|---|---|
| JVM Anatomy Quarks | https://shipilev.net/jvm/anatomy-quarks/ | Набор полезных микро-статей о разных составляющих JVM от Шипилёва |
* https://richardstartin.github.io/ автор много пишет про перформанс в jvm 
* http://psy-lob-saw.blogspot.com/ - блог о перформансе в jvm
 
# Distributed Systems, DBMS
## General
| Name | Link | Commentary |
|---|---|---|
| Bigtable: A Distributed Storage System for Structured Data | https://static.googleusercontent.com/media/research.google.com/en/archive/bigtable-osdi06.pdf | Легендарный пейпер от Google оказавший огромное влияние на мир IT. Обязателен к прочтению |
| Database Internals: A Deep Dive into How Distributed Data Systems Work | https://www.databass.dev/ | Отличная книга про внутренне устройство современных баз данных и распределённых систем |
| Designing Data-Intensive Applications | https://dataintensive.net/ | Must-Read для любого разработчика. Лучшая референсная книга про распределённые системы и базы данных |
| Dynamo: Amazon’s Highly Available Key-value Store | https://www.allthingsdistributed.com/files/amazon-dynamo-sosp2007.pdf | Легендарный пейпер (x2) от Amazon оказавший огромное влияние на мир IT. Обязателен к прочтению |
| NewSQL: SQL никуда не уходит (Константин Осипов) | https://youtu.be/_8OZcgOKUyk | Лайтовое рассуждение почему NoSQL трансформируется в NewSQL |
| Лекции по внутреннастям баз данных от мейл ру. | https://www.youtube.com/playlist?list=PLrCZzMib1e9r6c-j8aW1JuETSyCBp9iAg | Лекции уже довольно старые 2014 год. Если хотите выучить рафт и паксес лучше послушать лекции Ромы, однако тут тоже много полезного и интересного |
| Лекции Романа Липовского о распределенных системах | https://www.youtube.com/playlist?list=PL4_hYwCyhAvaYKF6HkyCximCvlExxxnrC | Лекции огонь, достаточно открыть плейлист и прочитать список тем как это станет ясно |
| Подходы к реализации шардинга в современных NoSQL-системах (Константин Осипов) | https://youtu.be/DfaTNXCsYRg | Название говорит само за себя. Доклад довольно тяжелый |

* https://lemire.me/en/#publications - Публикации Daniel Lemire, интересное про performance в обработке данных (биты, байтики и т.п.). Автор Roaring Bitmap.
* https://vldb.org/pvldb/vol15-volume-info/ - Публикации с конференции VLDB (Very Large Databases) https://dl.acm.org/conference/mod - Публикации SIGMOD (Special Interest Group of Management of Data)

## Cassandra
| Name | Link | Commentary |
|---|---|---|
| Cassandra: The Definitive Guide: Distributed Data at Web Scale | https://www.amazon.com/Cassandra-Definitive-Guide-Distributed-Scale/dp/1098115163 | Вводная книга по работе с Кассандрой |
| Cassandra Patterns | https://speakerdeck.com/sherman/cassandra-patterns | Хороший, но немного устаревший доклад о типичных подходах к построению схемы данных в кассандре |
| Лекция Романа Липовского о кассандре и динамо | https://youtu.be/qQLOofy8SYI | Хорошо объясняет мотивацию тех или иных архитектурных решений |

## Избранные доклады с Hydra
| Name | Link | Commentary |
|---|---|---|
| Распределен ные транзакции в YDB | https://2019.hydraconf.com/2019/talks/3ubxfwi4ikpxdjcdqswjih/ | Интересный доклад как на практике реализовали идеи из [Calvin](https://blog.acolyer.org/2019/03/29/calvin-fast-distributed-transactions-for-partitioned-database-systems/) |
| Scalable postgresql (Yugabyte) | https://2020.hydraconf.com/2020/msk/talks/6llhavpi9hi5yeibx64csi | Если вы когда-нибудь будете делать распределенную базу данных, например, то хорошей стратегией будет взять популярный продукт и переписать его внутри, добавив в него те свойства, которых нет у оригинала. Например, Yugabyte взял query layer от Postgresql и сделал как бы распределенный Postgresql. Еще примеры: [Redpanda](https://redpanda.com/), [Scylla](https://www.scylladb.com/) |
| CAP Theorem — two decades and few clouds later | https://2021.hydraconf.com/2021/msk/talks/5suwvc3iunj6y0twg8hz3v/ | Снова про CAP теорему, но уже с позиции прошедших лет |
| The official ten-year retrospective of NewSQL databases | https://2021.hydraconf.com/2021/msk/talks/1pthdabh5d2mn3fm2h7kme/ | Andy Pavlo рассуждает на тему эволюции баз данных. Это всегда интересно. Рекомендую не пропускать его выступления |

## Apache Ignite
| Name | Link | Commentary |
|---|---|---|
| Aндрей Гура - Архитектура хранилища распределенной базы данных Apache Ignite: решения и компромиссы | https://youtu.be/vpbmYA0Wsbg | Хороший доклад о том, почему вообще в in-memory БД добавляют персистентное хранение на диски (ради рестартов) |
| Командная разработка сложных продуктов (Владимир Озеров) | https://youtu.be/jR1vqZqzD-U | Озеров руководил разработкой в GridGain, потом ещё работал над Хазелкастом |
| B+ дерево в реальном проекте | https://habr.com/ru/company/sberbank/blog/413749/ | Довольно старая статья о реализации B+ дерева в игнайте |

## YDB
| Name | Link | Commentary |
|---|---|---|
| Yandex Database – как мы обеспечиваем отказоустойчивость (Владислав Кузнецов) | https://youtu.be/dCpfGJ35kK8 | Отличный доклад описывает архитектуру YDB как слоеный пирог |

## Clickhouse
| Name | Link | Commentary |
|---|---|---|
| Как работает ClickHouse | https://youtu.be/vbhSrZxm66E | Немного сумбурная, но за-то весьма подробная лекция о том как что и почему устроено в ClickHouse |
| Что нужно знать об архитектуре ClickHouse (Алексей Зателепин) | https://youtu.be/PLMSA_gDdyM | Доклад тоже рассказывает о внутренностях ClickHouse, но чуть меньше зато затрагивает вопросы репликации и шардирования |

## Assorted
| Name | Link | Commentary |
|---|---|---|
| One Size Fits None - (Everything You Learned in Your DBMS Class is Wrong) | https://slideshot.epfl.ch/play/suri_stonebraker | В докладе Майкл показывает почему традиционные реляционные базы данных архитектурно устарели и нужно создавать новые системы. Его идеи лежат в основе Tarantool и Voltdb, а также многих других распределенных СУБД |

# Highload, SRE
| Name | Link | Commentary |
|---|---|---|
| Изучаем Latency: теория массового обслуживания | https://habr.com/ru/company/yandex/blog/431650/ | За простоватым названием скрывается топовая статья для бекендеров |
| The System Design Primer | https://github.com/donnemartin/system-design-primer/blob/master/README.md | Страница про дизайн систем |
| MathOps или математика в мониторинге | https://habr.com/ru/company/oleg-bunin/blog/350666/ | Неплохая вводная статья о том, как нужно анализировать и интерпретировать метрики работы приложения |
* https://habr.com/ru/company/yandex/blog/579778/ 
* https://habr.com/ru/post/578728/

# Algorithms
| Name | Link | Commentary |
|---|---|---|
| Современные структуры данных | https://youtu.be/eVDWMRPsjo4 | Название не очень удачное, но тут рассказывают о всяких эффективных по памяти структурах типа LogLogCounter-а |
| Коты в коробочках, или Компактные структуры данных | https://habr.com/ru/company/vk/blog/479822/ | Прикольная вводная статья рассказывающая про структуры данных, которые стараются быть минимальными с точки зрения занимаемой памяти для разных разряженных структур |
| Double-Array Trie | https://linux.thai.net/~thep/datrie/datrie.html | Реализация Trie на двух массивах (описание и библиотека на C) |
| Плейлист кажется всех лекций и докладов Максима Бабенко | https://www.youtube.com/playlist?list=PLuWypj7F_mQmz5rIkupGd3AiI6hpVrOYx | Максим Бабенко руководит разработкой YT в Яндексе. К сожалению у некоторых лекций довольно плохое качество записи. По он всегда говорит о каких-то продвинутых штуках и в самом худшем случае их можно потом загуглить |

# Type systems
| Name | Link | Commentary |
|---|---|---|
| «Алгебраические эффекты» человеческим языком | https://m.habr.com/ru/post/470718/ | todo |
| Как извлечь пользу из статической типизации | https://habr.com/ru/post/550958/ | Статья о том как простые и не очень трюки с системой типов Java помогут помочь сделать код надежнее |
| Полиморфизм простыми словами | https://medium.com/devschacht/polymorphism-207d9f9cd78 | Прекрасный лонгрид про полиморфизм |
| How to Write an Equality Method in Java | https://www.artima.com/lejava/articles/equality.html | Старая статья Одерски, которая показывает что написать корректный метод сравнения в Java для любого класса невозможно |
| Counterexamples in Type Systems | https://counterexamples.org/ | Целый сайт посвещенный проблемам которые возникают при разработки систем типов. Чтиво непростое, хорошо бы знать Haskell и OCaml, примеров на C-like языках совсем не много |
| Управление ресурсами: линейные типы спешат на помощь (Виталий Брагилевский) | https://youtu.be/6fcEIPCa64c | Простой и понятный доклад Брагилевского о том, что такое линейные типы |
| DOT for kiddies (Виталий Брагилевский) | https://youtu.be/zUrEo7GMVRE | Короткая лекция про формальную систему DOT в которой можно описать синтаксис Scala |
