---
layout: page
title: Чат админов Oracle
permalink: /chat/
---


<h3>IRC (Чат)</h3><br/>


Можно подключиться в браузере:<br/>
Достаточно просто перейти <a href="http://webchat.freenode.net/?channels=%23oracle-dba">по ссылке</a> и ввести login и capcha.


Если постоянно использовать чат, то можно и какой-нибудь клиент установить.

В Windows это может быть MIRC (Я его последний рас использовал лет 12 назад, но он и тогда был крут.) [Оказывается он платный!]<br/>
Сейчас пользуюсь Linux и использую Pigdig.

Server для подключения: irc.freenode.net

Чтобы переключиться на канал. Можно выполнить команду:


    /join #oracle-dba

Или с помощью каких-нибудь менюшек. В PigDig это Conversation -> Join Chat и указать #oracle-dba


<strong>Не обещаю, что там кто-нибудь будет, но возможность сидеть в чате есть.</strong>

<br/><br/>

<div align="center">
    <img src="/website/chat/pigdig.png" border="0" alt="PigDig chat"
    />
</div>

<br/><br/>

Если вам не ответили, это не значит что вас игнорируют. Просто следить за чатом не всегда получается.

<br/><br/>


<h3>Консольний Linux IRC клиент - irssi</h3>

В Ubuntu: <br/><br/>

    $ sudo apt-get install irssi

<br/>

    $ irssi

<br/>

    /connect irc.freenode.net
    /nick username
    /join #oracle-dba


<br/>

    Switch windows where # is 0-9:
    Alt-#
    Query a user:
    /q <nick>
    List users in a channel:
    /n
    Private message a user:
    /m <nick> message
    Display a channels topic:
    /topic
    Perform an action: (e.g. <nick> scratches his nose)
    /me scratches his nose
    To mark yourself as away:
    /away away_message



<br/><br/>
Команды:<br/>
http://www.ircbeginner.com/ircinfo/ircc-commands.html
