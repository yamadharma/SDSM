# 5. ACL и NAT

Продолжаем развитие нашей маленькой уютной сети Лифт ми Ап. Мы уже обсудили вопросы маршрутизации и стабильности, и теперь, наконец, выросли для подключения к Интернету. Довольно заточения в рамках нашей корпоративной среды!  
Но с развитием появляются и новые проблемы.  
Сначала вирус парализовал веб-сервер, потом кто-то притаранил червя, который распространился в сети, заняв часть полосы пропускания. А ещё какой-то злодей повадился подбирать пароли на ssh к серверу.  
А представляете, что начнётся, когда мы подключимся к Интернету?!  
Итак, сегодня:  
1\) учимся настраивать различные списки контроля доступа \(Access Control List\)  
2\) пытаемся понять разницу между ограничением входящего и исходящего трафика  
3\) разбираемся с тем, как работает NAT, его плюсы, минусы и возможности  
4\) на практике организуем подключение к Интернету через NAT и увеличим безопасность сети, используя списки доступа.

[Видео версия](https://youtu.be/OHSmt_TS2j8)
