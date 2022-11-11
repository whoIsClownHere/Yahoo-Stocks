# Stock-history-on-PyQT6
PyQT6 project that parses, receives and processes data from Yahoo Finance

## Проект на PyQT6 для отслеживания инвестиционого портфеля

С помощью программы можно легко отслеживать полностью активность инвестиционного портфеля, данные для отслеживания берутся с Yahoo Finance. Пользователю
необходимо ввести названия тикеров акций, вес каждой акции в портфели, дата покупки акций и дата продажи акций. После чего в csv таблице можно легко
отследить данные о движении инвестиционного портфеля в процентном соотношении. Пользователь также может построить несколько типов графиков: общее 
движение инвестиционного портфеля, соотношение количества дней, когда акции приносили убыток и дней, когда приносили прибыль, график "ящик с усами",
который поможет понять медиану, размах и другую полезную информацию. В приложении также доступна важная информация, которая формируется из csv таблицы по 
данным о движении инвестиционного портфеля. Важная информация представляет собой csv таблицу, в которой находится количество дней, среднее арифметическое
всех показателей, стандартное отклонение, минимальное значение, максимальное значение, числа, которые находятся на 25%, 50%, 75% от длины индексах,
из csv таблицы по данным о движении инвестиционного портфеля. Также реализована история ввода данных в приложение пользователем, для этого используется
технология sqLite, которая представляет из себя базу данных.


Технологии:

1. PyQt6
2. pandas
3. yfinance
4. matplotlib
5. sqlite3

-----------------------------------------------------------------------------------------
© Авторская собственность
