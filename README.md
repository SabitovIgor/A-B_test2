# A-B_test2
Моя задача провести оценку результатов A/B-теста. В моем распоряжении есть датасет с действиями пользователей, техническое задание и несколько вспомогательных датасетов.
- Оценить корректность проведения теста
- Проанализировать результаты теста

# Библиотеки:
pandas, numpy, seaborn, matplotlib

# Вывод:
По корректности проведения А-В теста в соответствии с заданием можно сделать следующие выводы:

отношение участников эксперемента 57:43, количество участников в группе А и В меньше 6000 человек
так же время проведения теста сопадает с проведением промоакции
Результаты А/В теста:

в эксперементальной группе залогинилось только 32 процента от пользователей, мы имеет катастрофически маленькую выборку, возможно это какой то технический сбой

воронки событий по группам ведут себя примерно одинаково, но статистически значимыми эту результаты считать нельзя

график LTV показал, что у пользователей эксперементальной группы хорошо увиличился этот показатель, стоит провести корректный тест для выявления этой гипотезы

z-test лишний раз подтвердил не состоятельность А/В теста

u-test подтвердил что показатели LTV в двух группах разные, тест статистически не значимый

По результатам А/В тест можно считать не успешным!
