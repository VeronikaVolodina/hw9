# hw9
Для начала я удалила все строки, нажав Правка-Операции со строками-Удалить пустые строки (Содер….)
![](https://github.com/VeronikaVolodina/hw9/blob/master/Безымянный.png)
Затем я применила такую формулу, как: Нов(ѣ|ъ|у)?город(ѣ|ъ|цю|у)?  , чтобы найти все упоминания о Новгороде в различной форме написания (Новѣгородѣ, Новъгородъ, Новгородцю, Новагорода, Новугороду)
Так, всего упоминаний Новгорода я нашла: 54.
![](https://github.com/VeronikaVolodina/hw9/blob/master/Безымянный2.png)
Также я нашла всех князей и города, имя и название которых оканчивается на "слав" (Ярославля, Ростиславъ, Ростиславу, Переяславлъ) с помощью формулы: [А-Я][а-я]+слав[^\s.,\?!:;-]
Всего упоминаний о князьях я нашла: 564.  
