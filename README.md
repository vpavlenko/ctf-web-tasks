Веб-таски на CTF
================

План рассказа
-------------

1. Логинимся на сайт. Инструменты разработчика в браузере. Какие протоколы используются.
Как устроено HTTP-взаимодействие.
Как слать HTTP-запросы (nc/telnet, [плагин к браузеру](https://chrome.google.com/webstore/detail/dev-http-client/aejoelaoggembcahagimdiliamlcdmfm), [requests](http://docs.python-requests.org/en/latest/user/quickstart/)).
GET/POST-запросы, отправка данных формы. Примеры хедеров. Куки. HTTPS. Base64.

2. Анализ трафика: wireshark, [cloudshark](cloudshark.org), tshark.

2. Как работает язык PHP и как из него вызывают SQL-запросы. SQL-инъекции.

3. Что такое XSS и CSRF. Какие защиты от них придуманы.


Таски
-----

[**picoCTF**](https://picoctf.com/problems)
- First Contact 40 (pcap)
> You notice that the indicator light near the robot’s antenna begins to blink. Perhaps the robot is connecting to a network? Using a wireless card and the network protocol analyzer Wireshark, you are able to create a PCAP file containing the packets sent over the network.
>
> You suspect that the robot is communicating with the crashed ship. Your goal is to find the location of the ship by inspecting the network traffic.
>
> You can perform the analysis online on [Cloudshark](http://www.cloudshark.org/captures/bc1c0a7fae2c)
or you can download the [PCAP file](https://picoctf.com/problems/first_contact.pcap).

- GETKey 50 (easy)
> There's bound to be a key on the spaceport's [hidden website](https://picoctf.com/problems/getquery/index.php)

- Yummy 60 (requests)
> You want to find out the docking bay numbers for space ships that are ready to launch. Luckily for you, [the website](https://picoctf.com/problems/yummy) for the docking bay ship status page doesn't seem so secure....
>
> Enter the docking bay for any of the ships that are awaiting launch.

- PHP2 (php)
> We found a [simple web page](https://picoctf.com/problems/php2/) that seems to want us to authenticate, but we can't figure out how... can you?

- PHP3 (sql)
> It looks like [this site](http://picoctf.com/problems/php3/) uses MD5 to hash passwords, but I don't think they're doing it quite right...
- Client-Side is the Best Side 75 (easy)
- Second Contact 85 (pcap)
- DDoS Detection 85 (pcap)
- Pretty Hard Programing 95 (php)
- Injection 110 (sql) (я ещё не решил её)
- PHP4 (sql)

[**ufoCTF**](http://ufologists.ictis.sfedu.ru/game) (осторожно, ufoCTF идёт только до конца марта)
- Ping (pcap)
- PRISM (pcap)
- Телепорты (requests)
- CookieMonster (easy)
- 404 (easy)
- FBI (easy)


Материалы
---------

[Web Security Pitfalls](https://www.cis.upenn.edu/~cis331/proj2.pdf) - включает задания по SQL, XSS и CSRF

[Безопасность веб-приложений (Тарас Иващенко, ШРИ)](http://tech.yandex.ru/education/shri/msk-2012/talks/540/)

[Продвинутая презентация по SQL-инъекциям](http://www.ptsecurity.ru/download/PT-devteev-Advanced-SQL-Injection.pdf)
