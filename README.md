# hw9
## *Повесть временных лет*
### Выполняя это задание, я работала в программе Sublime Text
### 1. Как я удаляла пустые строки:
#### Вначале я просто удалила пустые строки, используя регулярное выражение : ^\n
# ![](https://github.com/alexandrapikalova/hw9/blob/master/1.png)
#### Потом я обнаружила в тексте другие пустые строки с пробелами. Чтобы от них избавиться, и я использовала следующее регулярное выражение : ^\s
# ![](https://github.com/alexandrapikalova/hw9/blob/master/2.png)
### 2. Как я искала всех князей и города, имя и название которых оканчивается на "слав"...:
#### Чтобы найти все имена собственные, оканчивавшиеся на -слав, я пользовалась регулярным выражением:
#### [А-Я][а-яѣ]+слав[а-яѣ]+
#### Всего упоминаний: 564
#### Так, в строке 49 мы можем заметить, что слово "славу" не выделелось.
# ![](https://github.com/alexandrapikalova/hw9/blob/master/3.png)
### 3. Упоминания Новгорода:
#### Здесь я использовала регулярное выражение: Нов.город+[^.?!;:-]
#### Всего упоминаний Новгорода нашла: 58
# ![](https://github.com/alexandrapikalova/hw9/blob/master/123.png)
### 4. Бонус
#### Здесь я применяла следующее регулярное выражение: ([!,.;:"?-])
#### Также я заменила на: $1 (пробел)
# ![](https://github.com/alexandrapikalova/hw9/blob/master/%D0%91%D0%BE%D0%BD%D1%83%D1%81.png)
