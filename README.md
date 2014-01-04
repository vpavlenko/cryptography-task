Криптография
============

План лекции
-----------

1. Шифры подстановки. Как ломать? ROT13: какая польза?

2. Одноразовый блокнот

3. Понятие о симметричных шифрах

4. Арифметика остатков. Диффи-Хеллман

5. Понятие об SSH, атака man-in-the-middle, ssh-ключи

6. Понятие об SSL, корневой сертификат, атаки

7. Понятие о хэшах

8. Электронные деньги (биткоины): монета, кошелёк, транзакция, блок, единая история, майнерство



Материалы
---------

1. Википедия: 
[ROT13](http://ru.wikipedia.org/wiki/ROT13),
[одноразовый блокнот](http://ru.wikipedia.org/wiki/%D0%9D%D0%B5%D0%B2%D0%B7%D0%BB%D0%B0%D0%BC%D1%8B%D0%B2%D0%B0%D0%B5%D0%BC%D1%8B%D0%B9_%D1%88%D0%B8%D1%84%D1%80),
[симметричный шифр DES](http://ru.wikipedia.org/wiki/DES), 
[протокол Диффи--Хеллмана](http://ru.wikipedia.org/wiki/%D0%9F%D1%80%D0%BE%D1%82%D0%BE%D0%BA%D0%BE%D0%BB_%D0%94%D0%B8%D1%84%D1%84%D0%B8_%E2%80%94_%D0%A5%D0%B5%D0%BB%D0%BB%D0%BC%D0%B0%D0%BD%D0%B0),
[RSA](http://ru.wikipedia.org/wiki/RSA),
[SSH](http://ru.wikipedia.org/wiki/SSH),
[SSL](http://ru.wikipedia.org/wiki/SSL),
[семейство хэшей SHA-2](http://ru.wikipedia.org/wiki/SHA-2),
[Bitcoin](http://ru.wikipedia.org/wiki/Bitcoin).

2. [S. Nakamoto. Bitcoin: A Peer-to-Peer Electronic Cash System](http://bitcoin.org/bitcoin.pdf)

3. [Вся история транзакций биткоинов](http://blockexplorer.com/)


Задание
-------

В этом задании вам предлагается отправить мне зашифрованное сообщение по открытому каналу связи, используя
ключи, заранее заготовленные мной.

В файле [open.py](../master/open.py) приведено описание подготовительных 
вычислений, которые я произвёл, чтобы дать вам возможность воспользоваться протоколом Диффи--Хеллмана или алгоритмом RSA.
Также там приведены сами получившиеся ключи. Значения всех переменных, которые там фигурируют, у меня имеются.

Ваши начальные действия:

1. Составьте какое-нибудь секретное сообщение.
2. Выложите на [pastebin.com](http://pastebin.com/) текст, содержащий сообщение, а также инструкцию по его расшифровке.
3. Пришлите мне на почту ссылку на выложенный текст.

Далее я попытаюсь расшифровать ваше сообщение, следуя вашей инструкции. Если у меня получится, то вы получите за это задание 20 баллов.

Затем я выложу ниже ссылку на pastebin.com, которую вы прислали. Т. е. каждому будет доступно и ваше сообщение, и ваша инструкция. После этого каждый из вас может попытаться устроить
"взлом": прочитать чужое сообщение. Каждый, кто осуществит хотя бы один взлом, получит дополнительные 20 баллов за задание. Каждому человеку нет смысла совершать второй и последующие взломы: премия за взлом начисляется один раз.

Если я посчитаю, что вина за успех взлома лежит на авторе сообщения, который выбрал недостаточно стойкий способ шифрования,
то он лишится своих 20 баллов за задание. Будьте осторожны в своих действиях.

В помощь вам привожу ссылки на онлайн-сервис симметричного шифрования: [online encrypt tool](http://www.tools4noobs.com/online_tools/encrypt/)
и [online decrypt tool](http://www.tools4noobs.com/online_tools/decrypt/).

Крайний срок сдачи сообщений: вечер 15 января.

Крайний срок сдачи взломов: вечер 31 января.


Присланные зашифрованные сообщения
----------------------------------

1. [Иван Сергеев](http://pastebin.com/zeuAB4w9)

