Веб-таски на CTF
================

План рассказа
-------------

1. Логинимся на сайт. Инструменты разработчика в браузере. Какие протоколы используются.
Как слать HTTP-запросы (nc/telnet, плагин к браузеру, питон).
GET/POST-запросы, отправка данных формы. Примеры хедеров. Куки. Base64.

2. Анализ трафика: wireshark, cloudshark, tshark.

2. Как работает язык PHP и как из него вызывают SQL-запросы. SQL-инъекции.

3. Что такое XSS и CSRF. Какие защиты от них придуманы.


Таски
-----

[picoCTF](https://picoctf.com/problems):
- First Contact 40: pcap

> You notice that the indicator light near the robot’s antenna begins to blink. Perhaps the robot is connecting to a network? Using a wireless card and the network protocol analyzer Wireshark, you are able to create a PCAP file containing the packets sent over the network.

> You suspect that the robot is communicating with the crashed ship. Your goal is to find the location of the ship by inspecting the network traffic.

> You can perform the analysis online on [Cloudshark](http://www.cloudshark.org/captures/bc1c0a7fae2c)
or you can download the [PCAP file](https://picoctf.com/problems/first_contact.pcap).

- Try Them All! 45: requests
- GETKey 50: easy
- Yummy 60: requests
- Client-Side is the Best Side 75: easy
- Second Contact 85: pcap
- PHP2: php
- DDoS Detection 85: pcap
- Pretty Hard Programing 95: php
- Injection 110: sql
- PHP3: sql
- PHP4: sql

[ufoCTF](http://ufologists.ictis.sfedu.ru/game) (осторожно, ufoCTF идёт только до конца марта)
- Ping: pcap
- PRISM: pcap
- Телепорты: requests
- CookieMonster: easy
- 404: easy
- FBI: easy


Материалы
---------

[Web Security Pitfalls](https://www.cis.upenn.edu/~cis331/proj2.pdf)

[Продвинутая презентация по SQL-инъекциям](http://www.ptsecurity.ru/download/PT-devteev-Advanced-SQL-Injection.pdf)

