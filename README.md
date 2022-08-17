# SurGard Ademco Contact ID

Протокол SurGard Ademco Contact ID (далее по тексту SurGard) представляет собой открытый протокол передачи извещений охранного, пожарного и технологического мониторинга. Этот протокол поддерживается всеми ведущими производителями контрольных панелей и мониторинговых приемников.

Взаимодействие между принимающим и передающим участниками осуществляется по каналу TCP/IP или по интерфейсу RS-232 (через COM-порт). 

В роли принимающего участника (сервера) как правило выступает пультовое программное обеспечение.

В роли передающего участника (клиента) выступают чаще выступают охранно-пожарные приборы. Стороннее программное обеспечение так же может выступать в роли клиента (например для выгрузки событий из мониторинговой программы).


## История появления
Изначально этот протокол являлс способом обмена информациис одноименноым оборудованием для мониторинга Sur-Gard (Sur-Gard System, Sur-Gard MLR2E и другие). Это много платформенный цифровые телефонные приемники, которые принимали сигналы по телефонным линиям и выводили информацию на принтер или компьютер. Эти телефонные приемники могли использовать несколько форматов сообщений, однако распространение получил формат Ademco Contact ID. Этот формат задокументирован в стандарте `SIA DC-05-1999.09`
