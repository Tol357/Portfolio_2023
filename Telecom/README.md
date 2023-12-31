# Определение неэффективных операторов в сервисе
Для этого проекта были использованы:

 - Python;
 - Pandas;
 - Plotly;
 - SciPy;
 - Tableau;
 - Power Point.
   
Для корректного определения неэффективных операторов была проведена предобработка предоставленных данных: заменены типы данных столбцов, заполнены пропущенные значения, удалены дубликаты.

Также были проведены расчеты и добавлены столбцы с длительностью ожидания ответа на звонок, со средней длительностью 1 звонка без и с учетом времени ожидания и время ожидания ответа на 1 звонок.

Затем были выявлены неэффективные операторы. Они пропускают много звонков и время ожидания ответа на звонок составляет длительное время.

После определения неэффективных операторов были проверены следующие гипотезы методом scipy.stats.ttest_ind:

 - Средняя длительность входящих внешних и исходящих внешних вызовов равна (без учета удержания и без учета пропущенных);
 - Среднее время ожидания при входящем внутреннем вызове и входящем внешнем вывове равна.

По результатам исследования были подготовлены дашборд и презентация.
