# Практическая работа 2 
## Выполнила: Ермакова Алена Денисовна, БСБО-06-23
Был создан модуль ActivityLifecycle. В данном модуле переопредилили основные методы жизненного цикла родительского класса, добавуили в разметку "activity_main.xml" поле текстового ввода "EditText" и реализовали отображение "activity", используя класс "Log". Также добавили в каждый метод жизненного цикла сообщение, содержащее сообщение имя метода. Далее запустили проект.
![](https://github.com/ErmakovaAD/Lesson2/blob/master/screnshots/5438376689748015129.jpg)
Будет ли вызван onCreate() после нажатия «Home» и возврата?
Нет, только если система выгрузит Activity из памяти.
Сохранится ли значение EditText после нажатия «Home» и возврата?
Нет, не сохранится
Сохранится ли значение EditText после нажатия «Back» и повторного запуска?
Нет, Activity уничтожается, и данные сбрасываются
Создали модуль MultyActivity, добавили кнопку и реализовали обработчик. Добавили "TextView" и инициализировали вызов:
![](https://github.com/ErmakovaAD/Lesson2/blob/master/screnshots/5438293393152272714.jpg)

и инициализировали вызов:

![](https://github.com/ErmakovaAD/Lesson2/blob/master/screnshots/5438119404027115347.jpg)

Создали модуль IntentFilter. Добавили кнопку "Открыть саайт" и обработчик для вызова веб-браузера, также добавили кнопку для передачи ФИО и университета:

![](https://github.com/ErmakovaAD/Lesson2/blob/master/screnshots/5438376689748015277.jpg)
![](https://github.com/ErmakovaAD/Lesson2/blob/master/screnshots/5438376689748015281.jpg)
![](https://github.com/ErmakovaAD/Lesson2/blob/master/screnshots/5438376689748015282.jpg)

Создали модуль ToastApp, добавили поле ввода и кнопку "Посчитать символы":

![](https://github.com/ErmakovaAD/Lesson2/blob/master/screnshots/5440787484956029520.jpg)
![](https://github.com/ErmakovaAD/Lesson2/blob/master/screnshots/5440787484956029521.jpg)

Создали модуль NotificationApp, добавили кнопку "SEND NOTIFICATION" и реализовали ее:

![](https://github.com/ErmakovaAD/Lesson2/blob/master/screnshots/5440787484956029592.jpg)
![](https://github.com/ErmakovaAD/Lesson2/blob/master/screnshots/5440787484956029647.jpg)

Создали модуль Dialog, сделали класс AlertDialogFragment и добавили кнопку "Show Dialog" и добаввили передачу данных в активити из диалога, сделав 3 метода:

![](https://github.com/ErmakovaAD/Lesson2/blob/master/screnshots/5440787484956029702.jpg)
![](https://github.com/ErmakovaAD/Lesson2/blob/master/screnshots/5440784667457484280.jpg)
![](https://github.com/ErmakovaAD/Lesson2/blob/master/screnshots/5440787484956029703.jpg)
![](https://github.com/ErmakovaAD/Lesson2/blob/master/screnshots/5440787484956029702.jpg)
![](https://github.com/ErmakovaAD/Lesson2/blob/master/screnshots/5440787484956029701.jpg)

Выполнили самостоятельную работу, создали 3 класса и сконструировали диалоговые окна, добвили 3 кнопки и реализовали вызов данных:

![](https://github.com/ErmakovaAD/Lesson2/blob/master/screnshots/5440787484956029710.jpg)
![](https://github.com/ErmakovaAD/Lesson2/blob/master/screnshots/5440787484956029712.jpg)
![](https://github.com/ErmakovaAD/Lesson2/blob/master/screnshots/5440787484956029713.jpg)
![](https://github.com/ErmakovaAD/Lesson2/blob/master/screnshots/5440787484956029714.jpg)
![](https://github.com/ErmakovaAD/Lesson2/blob/master/screnshots/5440787484956029716.jpg)
![](https://github.com/ErmakovaAD/Lesson2/blob/master/screnshots/5440787484956029720.jpg)
