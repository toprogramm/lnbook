# Освоение Lightning Network

[![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

СТАТУС: Первое издание опубликованное 21 Декабря, 2021

<img src="images/cover_thumb.png" width=200 alt="Mastering Lightning Cover">

## О книге
«Освоение Lightning Network» — это книга O'Reilly Media авторов Андреас М. Антонопулос ([@aantonop](https://twitter.com/aantonop)), Олаолува Осунтокун ([@roasbeef](https://twitter.com/roasbeef)), Рене Пикхардт ([@renepickhardt](https://twitter.com/renepickhardt)). Она была опубликована 21 декабря 2021 года в мягкой обложке и в электронном варанте (e-book) компанией O'Reilly Media. Ее можно найти везде, где продаются книги (в английском варианте, в США). В этом репозитории содержится копия книги, опубликованная O'Reilly Media, под тегом [firstedition_firstprint](https://github.com/lnbook/lnbook/releases/tag/firstedition_firstprint).

В книге описывается Lightning Network (LN), Peer-to-Peer (Равный-с-Равным) протокол, работающий поверх Биткойна и других блокчейнов, который обеспечивает скорость, безопасность, микроплатежи.

Книга подходит техническим читателям, понимающим основы Биткойна и других открытых блокчейнов.

## Содержание

### Предисловие

*  [Обложка](cover.html) 
*  [Титульная страница](titlepage.html)
*  [Авторские права](copyright.html)
*  [Оглавление](toc.html)
*  [Предисловие](preface.asciidoc)

### Часть 1

*  [Часть 1 - Intro](part_1_divider.asciidoc)  
*  [Введение](01_introduction.asciidoc)
*  [Начало Работы](02_getting_started.asciidoc)
*  [Как Работает Lightning Network](03_how_ln_works.asciidoc)
*  [Программное Обеспечение Узлов Lightning](04_node_client.asciidoc)
*  [Управление Узлом Сети Lightning](05_node_operations.asciidoc)

### Часть 2

*  [Часть 2 - Intro](part_2_divider.asciidoc)
*  [Архитектура Lightning Network](06_lightning_architecture.asciidoc)
*  [Каналы Оплаты](07_payment_channels.asciidoc)
*  [Маршрутизация Платежных Каналов в Сети ](08_routing_htlcs.asciidoc)
*  [Работа Канала и  Пересылка Платежей](09_channel_operation.asciidoc)
*  [Луковая Маршрутизация](10_onion_routing.asciidoc)
*  [Gossip and the Channel Graph](11_gossip_channel_graph.asciidoc)
*  [Поиск Пути и Доставка Платежей](12_path_finding.asciidoc)
*  [Проводной протокол(Wire Protocol): Кадрирование и Расширяемость](13_wire_protocol.asciidoc)
*  [Траспортировка зашифрованных Lightning сообщений ](14_encrypted_transport.asciidoc)
*  [Lightning Запросы на Оплату](15_payment_requests.asciidoc)
*  [Безопасность и конфиденциальность Lightning Network](16_security_privacy_ln.asciidoc)
*  [Заключение ](17_conclusion.asciidoc)

### Приложения 

*  [Обзор основ Bitcoin](appendix_bitcoin_fundamentals_review.asciidoc)
*  [Основы Docker](appendix_docker_basics.asciidoc)
*  [Сообщения Протокола](appendix_protocol_messages.asciidoc)

### Глоссарий

*  [Глоссарий](glossary.asciidoc)

### Биография Автора и Колофон

*  [Биография Автора](author_bio.html)
*  [Колофон](colo.html)

## Лицензия Creative Commons с указанием авторства Sharealike

Mastering the Lightning Network выпускается под лицензией Creative Commons CC-BY-SA 4.0. Полные условия лицензии можно найти здесь:

[![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Text" property="dct:title" rel="dct:type">Mastering the Lightning Network</span> by <span xmlns:cc="http://creativecommons.org/ns#" property="cc:attributionName">Andreas M. Antonopoulos, Olaoluwa Osuntokun, Rene Pickhardt</span> лицензия выдана на основании  <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.<br />Базирована на Работе <a xmlns:dct="http://purl.org/dc/terms/" href="https://github.com/lnbook/lnbook" rel="dct:source">https://github.com/lnbook/lnbook</a>.

Эта лицензия, соответствующая «Свободной культуре», была одобрена нашим издателем O'Reilly Media (http://oreilly.com), который понимает ценность открытого исходного кода. O'Reilly Media — не только лучший в мире издатель технической литературы, но и активный сторонник открытой культуры и обмена знаниями.

Спасибо О'Рейли Медиа!

## Переводы и производные версии (например, электронные книги в формате PDF, HTML, EPUB)

Текущая лицензия разрешает производную работу, такую как независимые переводы, а также производство и распространение PDF, HTML или других производных изображений исходного ASCIIDOC. *Лицензия не распространяется на интеллектуальную собственность O'Reilly Media, такую как титульная страница.*

Если вы заинтересованы в переводе этой книги, см. [TRANSLATING.md](TRANSLATING.md)

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
