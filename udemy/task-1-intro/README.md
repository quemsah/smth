###Задание 1. Подготавливаем проект к дальнейшим урокам

В файле скрипта создать 2 переменные (money и time), которые будут получать данные от пользователя:
-     Первая будет спрашивать "Ваш бюджет на месяц?"
-     Вторая "Введите дату в формате YYYY-MM-DD"
Создать объект appData, который будет содержать такие данные:
-      бюджет (передаем сюда переменную из п.2)
-      данные времени - timeData (передаем сюда переменную из п.2)
-      объект с обязательными расходами - expenses (смотри пункт 4)
-      объект с необязательными расходами - optionalExpenses (оставляем пока пустым)
-      массив данных с доп. доходом - income (оставляем пока пустым)
-      свойство savings (выставляем его как false)
Задать пользователю по 2 раза вопросы:
“Введите обязательную статью расходов в этом месяце”
“Во сколько обойдется?”
 Записать ответы в объект expenses в формате:
expenses: {
    “ответ на первый вопрос” : “ответ на второй вопрос”
    }
Вывести на экран пользователя бюджет на 1 день (брать месяц за 30 дней, использовать alert)